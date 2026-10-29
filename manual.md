---
layout: default
title: User guide (draft)
description: How to use Straightforward on iPhone, including location awareness, intersections, places, transit, ride announcements, virtual exploration, Straightpoint, and Siri.
permalink: /manual/
---

# Straightforward user guide

**First draft · October 29, 2026 · iPhone beta 0.1.0, build 30.** This manual describes the controls and behavior in that build. It is a working draft, checked against the app's source rather than a claim that every workflow has been tested on a phone. Please send corrections and questions to [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com).

Straightforward brings location information, places, intersections, and transit together. You can read information when you want it, choose automatic announcements, point toward a destination with Straightpoint, or explore a place virtually without going there.

<nav aria-labelledby="contents">
<h2 id="contents">Contents</h2>
<ul>
<li><a href="#getting-started">Getting started and permissions</a></li>
<li><a href="#getting-around">Getting around with VoiceOver</a></li>
<li><a href="#location">Location and automatic awareness</a></li>
<li><a href="#intersections">Intersections and crossing details</a></li>
<li><a href="#places">Finding places and addresses</a></li>
<li><a href="#favorites">Favorites and saving your current location</a></li>
<li><a href="#straightpoint">Pointing toward a place with Straightpoint</a></li>
<li><a href="#transit">Transit stops, departures, and trip stops</a></li>
<li><a href="#ride">Live ride announcements and get-off reminders</a></li>
<li><a href="#virtual-walk">Virtual street exploration</a></li>
<li><a href="#virtual-ride">Virtual bus rides</a></li>
<li><a href="#assistant">Ask Straightforward in the app</a></li>
<li><a href="#siri">Ask Straightforward through Siri</a></li>
<li><a href="#settings">Settings, voices, units, and audio</a></li>
<li><a href="#diagnostics">Feedback and diagnostic logs</a></li>
<li><a href="#troubleshooting">Troubleshooting</a></li>
<li><a href="#glossary">Short glossary</a></li>
</ul>
</nav>

<h2 id="getting-started">Getting started and permissions</h2>

### Install the beta

Straightforward is an iPhone beta distributed through Apple's TestFlight app, not a public App Store download. If you already have an invitation, open it and follow TestFlight's installation steps. To request an invitation, email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com). This guide does not provide an unrestricted public enrollment link. Android is not available yet.

The app appears on your Home Screen as **Straightforward**; its full name is **Straightforward Navigation**. Open TestFlight to check for a newer invited build if your controls differ from this draft.

### Allow location access

1. Open Straightforward and select **Location**.
2. When iOS asks for location access, allow access while using the app. Keep **Precise Location** enabled for useful distances, street context, and transit stops.
3. Let the phone obtain a location. Read the status on Location; if acquisition fails, use **Retry location**.
4. When you choose a feature that works while locked or in another app—Background awareness, live Straightpoint, or a live ride—the app requests the additional **Always** location permission it needs. Follow the permission explanation and iOS prompts.

You do not need to enable every background feature. Straightpoint and ride announcements have their own location use; they do not require the Background awareness switch to be on. If permission was denied, use **Open location settings** when offered, or change Straightforward's location permission in iPhone Settings, then return to the app.

Online searches, road information, and transit lookups generally need an internet connection. A saved place remains saved without one, but that does not make all nearby data or trip information available offline.

### Set up sound for your device

Use your normal iPhone audio controls to select the speaker, headphones, hearing aids, or other hearing device you want. In **Settings → Location speech**, choose a voice and use **Preview voice**. If speech starts late or loses its first words on a hearing device, try **Keep hearing device audio connected**. [Audio settings](#settings) explains this option and its battery tradeoff.

<h2 id="getting-around">Getting around with VoiceOver</h2>

The five bottom tabs are, in order: **Location**, **Intersections**, **POIs**, **Transit**, and **Settings**. **Ask Straightforward** is a separate entry above the tabs, not a sixth tab. Details, favorites, selectors, and ride configuration open within the current tab. Use the ordinary iOS **Back** control to return.

In this manual, **activate** means double-tap a focused control with VoiceOver, or tap it without VoiceOver. Swipe left or right to move between controls. You can use VoiceOver's Headings rotor to find screen headings.

Several rows have secondary actions. With VoiceOver, focus the row, select **Actions** in the rotor if necessary, swipe up or down to choose an action, and double-tap to perform it. Without VoiceOver, open the row's visible **More** menu for the same commands. More is not always a separate VoiceOver focus stop because its commands are already on the row.

An announcement switch is different: activate the row to turn automatic announcements on or off. Its current information remains readable either way. An adjustable control, such as a speed or volume slider, uses VoiceOver swipes up and down to change the value; without VoiceOver, use its slider or the accompanying controls where provided.

<h2 id="location">Location and automatic awareness</h2>

Open **Location**. Its heading is **Location and awareness**. The status explains whether the current position is available, updating, or limited.

### Read your surroundings

Move through the information rows to read:

- **Phone facing:** the direction the phone points, using its compass.
- **Facing intersection:** a nearby intersection in the phone's facing direction. If none qualifies, the row says so.
- **Nearest intersection:** the closest identified intersection, whether or not it is ahead of you.
- **Nearest POI:** the nearby place identified by the place provider, with available category, distance, and direction.
- **Heading:** your direction of travel, determined from movement, not from how you hold the phone.
- **Approaching intersection:** an intersection ahead along your travel direction, with distance and available crossing information.
- Address fields, including **Street number**, **Street**, neighborhood, city, state or region, postal code, and country, where available.

Phone facing can work while you are stationary. Heading and Approaching intersection need usable movement evidence; turning the phone does not establish a travel direction. Facing and Nearest intersection do not necessarily identify the same crossing.

Live address information comes from the location provider. In virtual mode, street information describes the mapped virtual position instead; do not read it as your physical address.

### Choose what the app announces

1. On **Location**, find an announcement-capable row, such as **Street**, **Street number**, **Heading**, **Approaching intersection**, or **Nearest POI**.
2. Activate its switch to choose whether changes are spoken automatically.
3. Leave off the fields you want to read only on demand. The values continue updating while their announcement switches are off.

Phone facing, Facing intersection, and Nearest intersection are informational rows, not automatic-announcement switches. Approaching-intersection speech uses distance milestones rather than announcing every small distance change. Nearest POI announces a change of place, not every update to the distance of the same place. Your switch choices are saved.

### Stop speech quickly

Use **Mute speech** near the start of Location. It becomes **Unmute speech**. This stops and suppresses app-owned spoken announcements, including location, ride speech, and Straightpoint speech. It does not mute VoiceOver, and it does not turn off separately enabled ride sounds, Straightpoint guidance tones, or haptics. Use their own settings to stop those channels.

### Continue awareness while locked or in another app

1. On **Location**, turn on **Background awareness**.
2. Complete any requested Always location permission steps.
3. Enable the individual information switches you want announced.
4. Lock the phone or use another app. Delivery depends on location availability and iOS background execution.
5. Return to Location and turn **Background awareness** off when you want to end that session.

The app remembers an enabled choice and may restore it on an ordinary later foreground launch when permission is still available. Force-quitting is not a way to schedule an automatic restart: open the app again to use it. Background awareness is separate from a live ride or Straightpoint, so turn those off separately if they are also running.

<h2 id="intersections">Intersections and crossing details</h2>

### Browse the current road

1. Open **Intersections**.
2. Read the current-road context and intersection rows. Each row includes an available distance and cardinal direction.
3. Use the **Nearest intersection** prefix to identify the nearest marked row. The list is geographic, not simply sorted closest first.
4. Activate a cross-street row to browse that street around the selected intersection.

On a mainly north–south road, the northward intersections come before your position and the southward ones after it. Mainly east–west roads use east and west. This order is for browsing a corridor; it does not change when you turn your phone.

### Explore another street and return

Activating a cross street opens a new street-browse page at the same physical intersection. The road you just left appears as the current intersection. You can activate another crossing to continue exploring. This changes the browsing context, not your physical GPS location.

Use **Reverse browse direction** to reverse the browsing direction, **Return to my current street** to restore the live-road context, or native **Back** to return to the previous browse page.

### Read crossing details

On a populated **Facing intersection**, **Nearest intersection**, **Approaching intersection**, or Intersections-list row, use **More → Open crossing details**, or its VoiceOver action. Read the linear details screen, then use **Back**.

Where mapped, details can include traffic control, pedestrian signals, accessible pedestrian signal features such as audible or vibrating indications and push buttons, tactile paving, kerbs, refuge islands, and crosswalk information. The screen identifies OpenStreetMap as its source and gives the data refresh date.

Approaching information may describe cross-street arms as left, right, ahead, or behind relative to your established travel direction. Those descriptions are not compass headings or instructions to cross. Missing mapped information means unknown, not that a feature is absent. This information does not indicate the current signal phase or tell you when it is safe to cross.

<h2 id="places">Finding places and addresses</h2>

A **POI**, or point of interest, is a mapped place such as a business, park, or public facility.

### Search near your position

1. Open **POIs**, whose screen heading is **Points of interest**.
2. Choose **Nearby**; VoiceOver calls this **Search nearby**.
3. Enter a business name, category, address, or destination in **Search for a place**.
4. Press the keyboard's **Search** key.
5. Read the result rows. Activate a result to open its in-app details, or use its secondary actions directly.

Nearby search starts within two miles. Use **Expand search area to …** or **Reduce search area to …** to move between the available radii: 2, 5, 10, 25, and 50 miles. The labels use your selected distance units. Changing radius repeats the current query at that radius. The minimum and maximum controls are disabled at their respective limits.

The unfiltered nearby list refreshes when you open the tab. **Refresh nearby places** retrieves nearby places; it is separate from submitting a named query with the keyboard Search key. Pull-to-refresh is also available.

### Search another city with Anywhere

1. On **POIs**, choose **Anywhere**, called **Search anywhere** by VoiceOver.
2. Enter a place or address, including its city or region when useful.
3. Press **Search**. Use **Repeat anywhere search** to repeat it later.

Anywhere is not limited to the selected nearby radius. Remote results do not pretend to have a meaningful live distance ranking from your phone. It is also the starting point for [virtual street exploration](#virtual-walk).

### Understand a result's directions

A result may include its name, category, address, distance, and direction. A phrase such as **southwest side of East 14th Street** describes the side of the address street. A bearing such as **northeast** describes where the place lies from your current position. Those are different facts; either may be unavailable.

Street-side information depends on the address and mapped road geometry. No annotation means it could not be determined, not that the place is in the middle of the road. Place listings can also be outdated; Straightforward's current Apple Maps place source does not reliably identify closed businesses.

### Use a place's actions

Focus a result and use its VoiceOver actions, or open **More**:

- **Open in maps** opens the selected place in your preferred external map app.
- **Walking directions** hands the destination to that map app for routing.
- **Watch with Straightpoint** selects it as your directional target.
- **Explore virtually from here** starts virtual exploration at the place.
- **Add to favorites** saves it; a saved result offers **Remove from favorites** instead.

The **Nearest POI** row on Location also provides the applicable place actions. Choose Apple Maps or Google Maps for external handoff in **Settings → General → Map provider**. This preference does not change Straightforward's search data: the current iPhone beta uses Apple MapKit for nearby places and searches.

<h2 id="favorites">Favorites and saving your current location</h2>

### Save and use a mapped place

1. Find a place on **POIs**.
2. Use **Add to favorites** on its row.
3. To find it again, open **POIs → View favorite places**.
4. Use the favorite's actions to open it in maps, request walking directions, watch it with Straightpoint, or remove it.

Favorites are stored locally. With a current position, distances are recalculated and the list is closest first. Without a current position, your favorites remain available alphabetically; an unknown distance is not shown as zero.

### Mark the point where you are standing

1. Open **Location** and let it obtain a current position.
2. Focus the **Location and awareness** heading and choose its **Save current location** VoiceOver action. Without VoiceOver, open the heading's **More** menu and choose the same command.
3. In **Name this location**, read the accuracy information and enter a name in **Location name**.
4. Activate **Save location**; the visible button says **Save**. Use **Cancel** to leave without saving.
5. Find the named coordinate in **POIs → View favorite places**.

The app captures the position when you invoke the command, then saves that coordinate after you confirm the name. You can use it for a meeting point or another spot that is not a listed business. Accuracy describes the phone's fix, not a promise of doorway precision. The saved coordinate uses coordinate-based map handoff rather than searching for a business with the same name.

<h2 id="straightpoint">Pointing toward a place with Straightpoint</h2>

Straightpoint tells you when your phone points toward one selected coordinate. It is straight-line orientation, not turn-by-turn navigation or a walkable route.

### Select a target and start feedback

1. Find a place, favorite, or Transit stop and use **Watch with Straightpoint**. You can also select targets with [Ask Straightforward](#assistant).
2. Open **Location** and find **Straightpoint**. Read the watched target, available distance, and geographic direction.
3. Turn the **Straightpoint** switch on. Complete the location permission steps if requested.
4. Turn the phone to face the target. When aligned, the enabled feedback channels indicate its direction. Turning away stops alignment feedback.

Selecting a target and enabling guidance are separate. Selecting does not turn an off switch on; if the switch is already on, selecting a target starts guidance after any required permission check. You do not have to walk to use the phone-facing direction.

Guidance tones and vibrations become more frequent nearer the target, and tones also change pitch. With announcements enabled, alignment can speak the target's name, current straight-line distance, and cardinal direction. A distinct **Near [place]** cue indicates proximity; a place coordinate may be inside a building rather than at its entrance.

### Pause, clear, and revisit a target

- Turn **Straightpoint** off to stop feedback while keeping the target.
- Turn it back on to guide toward the same target again.
- On its Location row, use **Clear Straightpoint watched place** to remove the target. This leaves the switch unchanged; on with **No watched place** is idle, not active guidance.
- Use **Open watched place in maps** or **Walking directions to watched place** for external map actions.
- For a watched transit stop, **Open bus stop times** opens its current Transit details and departures.

The readable target distance is independent of whether guidance is on or the phone is aligned. If the position is stale or unavailable, the app identifies that rather than presenting an old distance as current.

### Choose tones, haptics, speech, and posture

Open **Settings → Straightpoint**. Independently set **Guidance tones**, **Haptics**, and **Announcements**. **Tone volume** controls tones, separately from location speech volume. Global Mute speech does not stop independently enabled guidance tones or haptics.

**Require level phone** is optional and off by default. Turn it on if you want Straightpoint feedback only while holding the phone roughly level. Raising it upright pauses feedback without clearing the target; lowering it resumes when usable sensor information is available. With this setting off, Straightpoint does not require a level phone. This setting is separate from virtual Auto mode's level-phone movement control.

Live Straightpoint is designed to continue while locked or in another app with the necessary permission and iOS execution. Sensor availability and audio routing still matter. It is not an automatic restart service after force-quit.

<h2 id="transit">Transit stops, departures, and trip stops</h2>

### Choose the physical stop you need

1. Open **Transit**. Nearby stops load automatically.
2. Read the stop name, service direction, available near-side/far-side placement, distance, routes, and destinations.
3. Choose the physical stop matching your intended route and direction. Stops on opposite curbs can have the same name and appear separately.
4. Activate the row for its stop details and departures. Use the visible **Refresh** control or pull-to-refresh to request updated nearby or detail data.

**Near side** means before the cross street in the bus service's direction; **far side** means after it. These labels describe the bus's approach, not your walking direction. Placement is experimental and appears only when the available geometry supports it. Missing direction or placement is not a reason to assume the opposite.

Stop rows and stop-detail headings offer **Open in maps**, **Walking directions**, and **Watch with Straightpoint** through More and VoiceOver actions. These use the exact selected stop coordinate, not a new search for its possibly shared name.

### Read departures and narrow the route list

1. Open a stop's details and read any service notices before the departure list.
2. Use **Filter routes** to open the route checkboxes.
3. Check the routes you want, then activate **Done**. No routes checked means all routes; checking several shows their combined departures.
4. Use **Clear filters** to return to all routes.
5. After the displayed departures, use **Load more departures** when offered. Each activation adds up to ten, to a maximum displayed range of 100.

Filters and the expanded departure range remain when you refresh or return from a trip. A newly opened stop has its own state. Focused stop details refresh periodically while in the foreground; you can also refresh explicitly.

**Scheduled** is timetable information. **Realtime** or **Predicted** indicates a usable matching current prediction, with update information. When a prediction is missing or stale, the schedule remains labeled as scheduled rather than becoming a live estimate. **Feed updated** is the source-data update, not the time your phone last checked it. Displayed clock times follow the phone's local time.

### Explore the stops on one departure

1. In stop details, activate an individual departure to open **Stops on this trip**.
2. Read the selected stop and ordered downstream stops for that actual dated trip.
3. Use **Show previous stops** to include earlier visits; **Hide previous stops** collapses them again.
4. Activate a trip-stop row to open that stop's details. Use **Back** to return to the same trip, then Back again for the origin's departures.

The list is not a union of every branch of a route. The selected departure establishes its trip and service day. Overnight transit service days can extend past midnight; do not substitute a different date or pattern simply because the route name is the same. A repeated stop on a loop represents a separate visit each time.

Each row's arrival is predicted only when there is a matching arrival prediction. **Scheduled arrival …, realtime arrival unavailable** is not a live estimate. Skipped or canceled visits are identified as not boarding. Read relevant notices and **Open publisher notice** for the agency's full instructions when available.

Coverage includes supported operators in the United States, Canada, and Germany, not every operator or feature in those countries. Schedules, live predictions, notices, stop placement, and live ride support have different availability. A stop with departures is not automatically a supported ride-watch trip.

<h2 id="ride">Live ride announcements and get-off reminders</h2>

Ride watch follows your position along one selected actual bus trip. It does not identify a bus merely because you are nearby, and it does not use the phone's pointing direction to track progress.

### Start from a departure

1. Open **Transit**, select a stop, and find the departure matching your actual route, direction, destination, and trip pattern.
2. On that departure, use **Start stop announcements** from More or VoiceOver actions. You can also open the departure and use the same action on **Stops on this trip**.
3. In configuration, turn **Announce each stop** on for ordinary stop announcements. Leave it off if you want only a selected get-off reminder.
4. Optionally activate **Choose get-off stop**. Select the appropriate occurrence on the trip, or use its **Get off here** action. The picker returns to configuration. Native Back leaves the picker without changing the destination.
5. Set **Speech**, **Sound**, and **Haptics** independently. These options are saved. Read any conditional drop-off instructions.
6. Activate **Start onboard**. Despite the label, you can start before boarding or partway through the trip. Start it while the app is foregrounded, complete permissions, and wait for success before locking the phone.
7. After a successful start, the app switches to **Location**, where **Current ride** shows the running watch.

An eligible trip-stop row also offers **Notify me before this stop**, which opens live configuration with that occurrence selected. Nothing starts simply by opening configuration or choosing a destination.

Choose the trip that represents the journey you will actually take, including the right branch or short turn. Starting late is supported, but this is not a promise that any departure with the same route number will work. If the required trip path or passenger-stop information is unavailable, the app explains that Start is unavailable; ordinary departures remain usable.

### Understand tracking and reminders

Ride watch needs a sequence of usable GPS fixes and vehicle movement to establish progress. A stationary wait before boarding does not expire the watch just because the bus has not moved. Once underway, **Next stop** and remaining-stop information appear when tracking is confident. **Tracking uncertain** means the app cannot currently establish that position; GPS loss, similar parallel paths, or repeated loop traversals can cause this.

With a get-off destination, reminders distinguish three stops away, your stop next, and approaching your stop. Ordinary stop announcements and the three-stop advance notice use an ordinary chime; an imminent destination has a distinct urgent cue. Missed stops and reminder stages are not queued for replay when you start late or regain GPS. Prediction times do not advance the tracker.

The watch can operate while locked or in another app after explicit Start with permission, subject to iOS execution and usable GPS. **Background awareness** and **Straightpoint** need not be enabled. Offline tracking may use last-known service information; it cannot discover a new cancellation without a successful update.

### End or resume a ride

On **Location → Current ride**, activate **End ride** to stop tracking and cues and remove the saved session. A running live ride has no user Pause control. Ending does not turn it into a resumable ride, and it does not clear a Straightpoint target.

After an interruption or later app launch, a retained ride may appear paused. Read the explanation and use **Resume**—called **Resume ride watch** by VoiceOver—only if offered, or **End ride** to discard it. A canceled, changed, or unsupported trip may require selecting a new trip instead. Opening the app alone does not resume a saved ride. If End reports incomplete cleanup, use its retry instruction rather than assuming it finished.

You can also start route-first announcements or change an active ride's get-off reminder with [Ask Straightforward](#assistant).

<h2 id="virtual-walk">Virtual street exploration</h2>

Virtual street exploration moves a simulated position along mapped roads. You remain physically where you are. Location, nearby places, and intersections can describe that virtual position while the mode is active.

### Choose a starting place

1. Open **POIs → Anywhere**.
2. Search for a place or address, including its city when needed.
3. On the intended result, choose **Explore virtually from here** through More or VoiceOver actions.
4. Open **Location** and find **Virtual mode: [place]** and its movement controls.

This action is also available on other place-like rows where offered. A nearby place can be a starting point too; Anywhere is useful for exploring a remote destination.

### Move in Manual mode

1. Select **Manual mode**; the visible button says **Manual**.
2. Focus **Virtual step distance** and swipe up or down to change it. Without VoiceOver, use **Less** and **More**.
3. Choose a distance or **Next intersection**.
4. Activate an available road-direction button to move along that mapped road.
5. Read the updated Location information or browse the other tabs for the new virtual surroundings.

Available directions follow the mapped road connections. You are not moving a free-floating point across buildings. Repeat direction activations to continue, or choose another direction at a junction.

### Move in Auto mode

1. In the virtual Location controls, select **Auto mode**; the visible button says **Auto**.
2. Choose **Virtual travel speed**: Slow walking, Normal walking, Fast walking, or Driving.
3. Turn yourself and the phone toward an available mapped road direction.
4. Hold the phone roughly level to move. Raise it upright to pause.
5. At a junction, Auto stops. Face another road to take it. To continue in the original direction, raise the phone upright and lower it again.

Walking uses footsteps; Driving uses a continuous movement sound. A junction has a separate brief cue. A repeating blocked sound means no mapped continuation in the current direction, not that there is a physical wall. Driving is a virtual pace, not a claim that the road can legally or physically be driven.

Leaving Location or backgrounding the app pauses Auto. Returning requires usable heading and tilt information. Switch to Manual or use Exit to end Auto; there is no separate Stop auto command.

### Start over, use virtual Straightpoint, and exit

**Start over**, called **Return to virtual starting place** by VoiceOver, returns the simulated position to the original starting point. It does not exit to live GPS or erase favorites.

To point toward a place from the simulated position, select **Watch with Straightpoint** while virtual, then turn on **Virtual Straightpoint** on Location. Phone facing and the virtual coordinate drive its feedback. This virtual watch is temporary and does not replace your saved live Straightpoint target.

Use **Exit virtual mode**—the visible button says **Exit**—to return to live location. Live modes active before street exploration can be restored, so check their switches. A physical ride suspended by entering virtual mode does not automatically resume; use its explicit Resume control after exit. Walking-directions handoff is restricted while virtual so an external map app does not silently route from your real GPS instead.

If **Waiting for road data** appears, wait for loading and try the direction again. Missing map data is not the same as reaching a dead end.

<h2 id="virtual-ride">Virtual bus rides</h2>

Virtual bus playback follows a selected actual trip's route rather than the phone's facing direction. It is separate from Manual and Auto street exploration.

1. Open **Transit**, choose a stop, and find a dated departure.
2. Use **Explore this trip virtually** on that departure, or on **Stops on this trip** after opening it.
3. Optionally use **Choose get-off stop** and select a visit; Back from the picker returns without changing the destination.
4. Set **Announce each stop**, **Speech**, **Sound**, and **Haptics** as desired.
5. Activate **Play virtual ride**.
6. On Location, use the **Virtual bus ride** controls: **Play** or **Pause**, **Next stop**, and the **Virtual bus speed** slider with Slow, Normal, Fast, and Very fast.
7. Activate **Exit virtual mode** to finish.

Playback begins at the departure's selected lookup stop. **Next stop** advances along the intervening path and then pauses; it is not a teleport. The selected get-off reminder and stop announcements use the shared ride feedback behavior.

Virtual bus playback is foreground-only. Leaving the app or locking the phone pauses it; activate Play after returning. It does not exercise physical GPS tracking. If there was a live ride, virtual entry suspends it and exit leaves it paused for explicit Resume.

<h2 id="assistant">Ask Straightforward in the app</h2>

The assistant is optional. It requires **iOS 27**, an Apple Intelligence-compatible iPhone, Apple Intelligence enabled, and Apple's system model downloaded and ready. These requirements apply to Ask Straightforward, not to all the app's ordinary features. If unavailable, read the explanation and continue using the tabs.

### Ask and choose a result

1. Activate **Ask Straightforward** above the five tabs, including from ordinary detail screens. You can also use the Location heading's More menu or VoiceOver action.
2. Type in the request field or use iOS keyboard dictation.
3. Press **Return** or activate **Send**.
4. Read the answer. With VoiceOver, a completed reply receives screen-reader focus; there is not a separate duplicate app-spoken answer.
5. If choices appear, use the numbered result buttons. Text pages show up to ten full results, with **Load more** and **Done with results** when applicable.

While choices are pending, the composer and Send are disabled. Use the result controls, not typed numbers or a new question. **Load more** continues the retained list. **Done with results**, or **No thanks** on an offered wider search, returns you to typing. After a target is successfully saved, selection finishes automatically and the composer becomes available; chat itself stays open. Older or expired result buttons can become unavailable—ask again rather than relying on an old choice.

Use ordinary **Back** to leave chat. It cancels running text work; idle conversation history and still-valid choices can remain when you return. Scroll through history manually. Text and Siri have separate conversations and choices; an unfinished text list is not Siri's current list.

### Things to ask

These requests use app information and actual search results:

- “What's my current address?” or “What's my street number?”
- “Which intersection am I facing?” or “What's my upcoming intersection?”
- “What's the nearest intersection?” or “What intersections are nearby?”
- “What POIs are nearby?” or “Find pizza nearby.”
- “What transit stops are nearby?” or “What bus routes are nearby?”
- “Set Straightpoint to the nearest Starbucks.”
- “Set Straightpoint on the southbound Bx9 stop at Broadway and Mosholu.”
- “Set Straightpoint to 123 Main Street, Seattle.”
- “Point at my saved hotel.” or “Point to the facing intersection.”
- “What's my Straightpoint target?” followed by “Start Straightpoint,” “Stop Straightpoint,” or “Clear Straightpoint.”

Use a name you actually saved for a favorite; there is no automatic built-in Home address. Saved-name matching can find both saved businesses and custom named coordinates. Multiple saved matches require a choice. Selecting a Straightpoint target does not enable guidance—ask **Start Straightpoint** separately if it is off.

Be explicit about **Nearby** or **Anywhere** for place targets. Nearby named-place resolution searches locally; Anywhere can find a remote place or address without a local radius. Anywhere is not worldwide transit search. The assistant does not silently widen a failed nearby search; when offered, **Search Anywhere for this name** is your choice.

### Start a ride by route name

You can ask for a nearby bus route without first opening a departure:

- “Announce the stops on the Bx9 southbound.”
- “Start announcements for the Bx9 southbound and tell me when we get to Broadway and Mosholu Avenue.”
- “Tell me when we get to Broadway and Mosholu Avenue on the Bx9.” This requests a reminder without every-stop announcements.

Choose among the actual route, destination, and stopping-pattern results. General compass wording helps describe the intended direction, but a route can bend and the available choices may include branches or short turns. Route discovery is nearby, not a global route catalog. A partial result set requires your explicit choice, and missing trip support or permission can prevent Start.

After a successful start, the app moves to **Location → Current ride**. During that ride, “Tell me when we get to Broadway and Mosholu Avenue” can add or change its destination using the active trip's visits. Repeated or ambiguous stop names need a choice. “What is my ride status?” reads the current watch; “End ride” ends it.

### Interpretation and privacy

The assistant interprets requests with Apple's on-device model and has no automatic cloud-model fallback. Online place and transit lookups are separate from interpretation. Siri recognition and keyboard dictation follow Apple's system settings; they are not a promise of app-controlled offline speech recognition.

The assistant cannot provide arbitrary turn-by-turn walking navigation, identify safe crossing moments, or control features outside its supported commands. It has no custom wake word or always-listening microphone mode. Conversations are memory-only, not a permanent saved chat archive. Diagnostic exports can contain location-bearing search information; [review the export explanation](#diagnostics) before sharing one.

<h2 id="siri">Ask Straightforward through Siri</h2>

Use the supported two-step invocation:

1. Say **“Hey Siri, Ask Straightforward.”**
2. Complete any first-use shortcut enablement confirmation.
3. Wait for **“What would you like to ask Straightforward?”**
4. Say your request, such as “What's my current address?” or “Announce the stops on the Bx9 southbound.”

Do not rely on combining the invocation and question into one phrase: Siri may send the trailing words to its own search instead of Straightforward.

Siri can read up to five concise choices at a time. Answer with a name, number, or distinguishing destination, say **more** for the next available page, or **done** to finish. A plain “first one” refers to the current page. If Siri cannot distinguish the result, narrow the choice using what it actually read. The dialogue has a limited lifetime and number of follow-ups; reopen Ask Straightforward if it expires, or use the in-app list.

The shortcut opens the app in the foreground to carry out the request, without opening the text composer. Siri owns its spoken dialogue. A result from a separate in-app conversation is not automatically a Siri choice.

<h2 id="settings">Settings, voices, units, and audio</h2>

Open **Settings** and choose **General**, **Location speech**, **Ride announcements**, **Straightpoint**, or **Diagnostics**. Each opens its own page with native Back. Changes save locally; read any save-failure message before assuming a change was kept.

### General

- **Distance units:** choose **Feet and miles** or **Meters and kilometers**. The default is feet and miles. The choice applies across current labels, VoiceOver, new assistant answers, guidance, search areas, and virtual distance controls; earlier chat text stays as originally written. Changing units does not change the physical size of a search or movement preset.
- **Map provider:** choose **Apple Maps** or **Google Maps** for external place opening and walking directions. It does not switch the source of search or Nearest POI data.

### Location speech

1. Activate **Language** to choose a language and see its available voices.
2. Choose a voice, or use **Voice** to change within the selected language. **System default** follows the system speech default.
3. Adjust **Speech rate**, **Pitch**, and **Volume**. With VoiceOver, focus the adjustable control and swipe up or down.
4. Activate **Preview voice** to hear the configuration. Unmute app speech first if necessary.
5. Use **Reload voices** if the installed list has changed, or **Reset speech settings** to restore defaults.

These settings do not change your VoiceOver voice. If a chosen installed voice is removed or unavailable, the app explains the fallback rather than losing your saved choice.

**Keep hearing device audio connected** is off by default. When enabled and eligible, it plays digital silence between announcements to help keep the audio stream connected. It applies while the app is foregrounded or user-started Background awareness is active, with speech unmuted. It can affect battery use and other audio. Turn it off if it is not useful for your particular hearing device; it is not a guarantee that every audio route behaves identically.

### Ride announcements

Ride announcements have an independent voice, initially **System default**. Choose **Independent ride voice**, then **Ride language** and **Ride voice**, or choose **Use location speech voice** to link the voice to Location speech. Linking does not copy Location speech rate, pitch, and volume.

Use **Preview ride voice** and **Reload ride voices** as needed. A preview is not a running ride. Configure whether a particular ride uses Speech, Sound, Haptics, or every-stop announcements in that ride's configuration, not on this voice page.

### Straightpoint and Diagnostics

The Straightpoint page contains **Guidance tones**, **Tone volume**, **Haptics**, **Announcements**, and **Require level phone**. See [Straightpoint setup](#straightpoint) for their separate effects. Diagnostics contains the export and clear controls described next.

<h2 id="diagnostics">Feedback and diagnostic logs</h2>

Send questions or corrections to [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com). For a beta issue, include your app build, what you tried, the control or message involved, and what happened instead. For an incorrect transit placement, include the stop, route, service direction, and the missing or wrong near-side/far-side detail. Send personal travel details privately, not in a public post.

### Share a diagnostic report

1. Reproduce the issue if practical, then open **Settings → Diagnostics**.
2. Choose **Share diagnostic logs**.
3. Read the location-privacy confirmation and choose **Continue** if you want to proceed.
4. In the iOS share sheet, choose a destination such as Messages or **Save to Files**. You approve any actual sending in the destination app.

If **Send diagnostic logs** is available, it opens a preaddressed email draft. Add a short issue description and use Mail's Send control. If Mail opens but cannot send, close the draft and use Share diagnostic logs instead; do not clear the evidence first. Opening a draft or share sheet does not itself mean delivery succeeded.

Logs are local and bounded, and can include precise real or virtual locations and dedicated search/target diagnostic details. Nothing is uploaded automatically by this export flow. Review the privacy explanation and choose who receives the file. Do not post a raw report publicly.

**Clear local diagnostic logs** removes the app's retained diagnostic evidence and its retained export copy. It does not remove a report you already sent or saved elsewhere. Export does not automatically clear the journal; canceling an export keeps the evidence.

<h2 id="troubleshooting">Troubleshooting</h2>

### Location or distances are unavailable

Read the Location status, check Precise Location and the allowed permission in iPhone Settings, then return and use **Retry location**. GPS can be limited indoors or between buildings. An unavailable address can be a separate provider issue even when the phone has a coordinate.

### Phone facing works, but Heading or Approaching intersection does not

Those rows need coherent travel movement, not a compass turn. Continue ordinary movement when appropriate and let the app collect usable fixes. Use Nearest intersection or Intersections for manual information in the meantime.

### There is no sound

Check **Unmute speech**, iPhone volume, and the selected audio route. Try **Settings → Location speech → Preview voice**. For Straightpoint, check its master switch, target, alignment, channel switches, Tone volume, and optional level-phone requirement. For a ride, check its Speech and Sound choices separately. VoiceOver volume and app speech settings are not the same control.

### A search has no results, or the service is unavailable

Check whether you selected Nearby or Anywhere. Submit a query with the keyboard Search key; expand a nearby search deliberately if useful. An unavailable service is not proof there are no places or stops. Check the connection and retry. For long-running or unsuccessful assistant lookups, return to the relevant ordinary tab or retry after the service becomes available.

### Road or crossing information is missing

**Some road data unavailable** means partial coverage; available results can still be useful. **Waiting for road data** in virtual mode is a loading or coverage problem, not an actual dead end. Allow loading, then retry a Manual direction, or let Auto retry. OpenStreetMap crossing details are incomplete in many places.

### A stop has no live prediction or no ride Start

Read scheduled departures as schedules, not tracking. Realtime requires a matching current agency prediction. Ride watch additionally needs suitable trip geometry and passenger-stop metadata; ordinary Transit can work without them. Choose the correct dated departure and read the specific unavailable explanation rather than substituting an unrelated trip.

### Current ride says Tracking uncertain

The watch is still running unless it says paused or ended. GPS gaps, ambiguous paths, and repeated route sections can prevent confident progress. Check the Current ride status; do not assume a frozen next-stop count is a current location. End ride remains available. If a restored ride is paused, explicitly Resume when offered.

### An assistant request does not go through

Check its readiness explanation: the assistant needs the supported OS, eligible hardware, enabled Apple Intelligence, and a ready model. Ordinary tabs do not need that model. If the text field is disabled because results are pending, choose a result or Done with results. If Siri searches the web, try the separate invocation, wait, then request sequence.

### Controls differ from this guide

Check your installed TestFlight build and whether a newer invited build is available. Earlier native clients can show an updated-client requirement for a feature; reloading a screen cannot add missing native capabilities. This draft describes build 30, not every development version.

<h2 id="glossary">Short glossary</h2>

- **POI:** point of interest; a listed place such as a business, park, or facility.
- **Phone facing:** the direction the phone points, from its compass.
- **Heading or travel course:** the direction you are moving, from location evidence.
- **Cardinal bearing:** north, northeast, east, and so on, from your position toward a coordinate.
- **Street side:** the geographic side of the place's address street, not its bearing from you.
- **Near side / far side:** before / after the cross street along the bus service's direction.
- **Straightpoint:** phone-facing feedback toward a selected coordinate in a straight line.
- **Scheduled / realtime:** a timetable time / a usable matching current prediction.
- **Actual dated trip:** one route journey on its transit service day, with its own ordered stop visits.
- **Virtual position:** the simulated location used for exploration, not your real GPS position.

[Return to contents](#contents)
