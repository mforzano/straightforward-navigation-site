---
layout: default
title: User guide (draft)
description: How to use Straightforward on iPhone, including location awareness, intersections, places, transit, ride announcements, virtual exploration, Straightpoint, and Siri.
permalink: /manual/
---

# Straightforward user guide

Draft for iPhone beta 0.1.0, build 30 · October 29, 2026

Straightforward puts your address, nearby places, intersections, and transit information together. You can check your surroundings, choose what gets announced as you move, or explore somewhere before you go there. Straightpoint helps you point your phone toward a place. It gives you a straight-line direction, not a walking route.

This guide describes build 30. If something is unclear or doesn't match what happens on your phone, email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com).

<nav aria-labelledby="contents">
<h2 id="contents">Contents</h2>
<ul>
<li><a href="#getting-started">Getting started</a></li>
<li><a href="#getting-around">Finding your way around the app</a></li>
<li><a href="#location">Checking your location</a></li>
<li><a href="#announcements">Announcements and background awareness</a></li>
<li><a href="#intersections">Exploring intersections</a></li>
<li><a href="#places">Finding places and addresses</a></li>
<li><a href="#favorites">Saving places</a></li>
<li><a href="#straightpoint">Pointing toward a place with Straightpoint</a></li>
<li><a href="#transit">Transit stops and departures</a></li>
<li><a href="#ride">Stop announcements and get-off reminders</a></li>
<li><a href="#virtual-walk">Exploring streets virtually</a></li>
<li><a href="#virtual-ride">Taking a virtual bus ride</a></li>
<li><a href="#assistant">Ask Straightforward</a></li>
<li><a href="#siri">Using Siri</a></li>
<li><a href="#settings">Voices, units, and other settings</a></li>
<li><a href="#internet">What needs an Internet connection?</a></li>
<li><a href="#diagnostics">Sending feedback and diagnostic logs</a></li>
<li><a href="#troubleshooting">Troubleshooting</a></li>
</ul>
</nav>

<h2 id="getting-started">Getting started</h2>

### Install Straightforward

Install Apple's TestFlight app, then open your Straightforward invitation and follow the installation steps. To request an invitation, email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com). The app appears on your Home Screen as **Straightforward**. Android is not available yet.

### Allow location access

1. Open Straightforward and select the **Location** tab.
2. Allow location access when iOS asks. Keep **Precise Location** on so the app can give you useful distances and street information.
3. Wait for the phone to find your position. If it can't, select **Retry location**.

You can start with access while using the app. Features that continue while the phone is locked or you're using another app request **Always** location permission when you turn them on. You can change permission later in iPhone Settings, or select **Open location settings** when the app offers it.

### Check the sound

Open **Settings → Location speech** and select **Preview voice**. You can choose a different voice and adjust its volume there. App speech has its own settings; changing it doesn't change your VoiceOver voice.

If your hearing device cuts off the beginning of announcements, try **Keep hearing device audio connected** on the same page. See [audio settings](#settings) for how it works.

<h2 id="getting-around">Finding your way around the app</h2>

The app has five tabs: **Location**, **Intersections**, **POIs**, **Transit**, and **Settings**. POI means point of interest: a place such as a store, restaurant, park, or public building. **Ask Straightforward**, above the tabs, opens the assistant.

In this guide, select a control by tapping it, or by focusing it and double-tapping with VoiceOver.

Some rows offer more than one action. With VoiceOver, focus the row and choose **Actions** in the rotor, then swipe up or down to find the command and double-tap. Without VoiceOver, tap the row's **More** menu for the same commands. For example, a place can offer walking directions, Straightpoint, and an option to save it.

For adjustable controls such as volume or speed, swipe up or down with VoiceOver to change the value. Without VoiceOver, adjust the slider or use the accompanying buttons where available.

<h2 id="location">Checking your location</h2>

Select the **Location** tab to check your address, the direction you're moving, nearby intersections, and the nearest place. The information updates as your position changes. If the app is still finding your position or can't get some information, it tells you on this screen.

The direction your phone points and the direction you're traveling are separate:

- **Phone facing** tells you where the phone points, using its compass. You can check this while standing still.
- **Heading** tells you which way you're moving. Turning the phone doesn't change your travel direction.

The intersection rows answer different questions:

- **Facing intersection** identifies an intersection in the direction your phone points, if one is available.
- **Nearest intersection** identifies the closest intersection, even if it's behind you.
- **Approaching intersection** identifies an intersection ahead along your direction of travel. It includes distance and available crossing information. The app needs enough movement to establish your travel direction before it can identify this intersection.

**Nearest POI** gives you a nearby place's name, with its category, distance, and direction where available. Its actions let you open it in maps, get walking directions, or select it for Straightpoint.

The address rows include **Street number**, **Street**, neighborhood, city, state or region, postal code, and country when the location provider supplies them. An address can be unavailable even when the phone knows its position.

When you're exploring virtually, Location describes your simulated position instead. [Virtual exploration](#virtual-walk) explains how to start and return to your real location.

<h2 id="announcements">Announcements and background awareness</h2>

Straightforward can announce changes as you move, so you don't have to keep checking the screen. You choose which information you want to hear. **Background awareness** lets those location announcements continue while your phone is locked or you're using another app.

These are two separate choices: the individual switches control *what* gets announced; Background awareness controls whether location awareness continues outside the app. Turning on Background awareness doesn't turn on every announcement.

### Choose your announcements

On the **Location** tab, turn on the switches for the information you want to hear, such as **Street**, **Street number**, **Heading**, **Approaching intersection**, or **Nearest POI**. Leave the others off. Your choices are saved.

Turning a row's announcement switch off doesn't stop its information from updating. You can still read the current value whenever you want. **Phone facing**, **Facing intersection**, and **Nearest intersection** are information rows, not announcement switches.

Approaching-intersection announcements tell you about the crossing at distance milestones rather than speaking every small change. Nearest POI announces when the nearest place changes, rather than repeating the same place as its distance changes.

### Keep location announcements going in the background

1. On **Location**, turn on **Background awareness**.
2. Complete the **Always** location permission steps if requested.
3. Check that the individual announcement switches you want are on.
4. Lock the phone or switch to another app.

Turn **Background awareness** off to stop background location awareness. Your individual announcement choices remain saved for the next time. The app also remembers the Background awareness choice and can restore it when you reopen the app, if permission is still available. After force-quitting, open Straightforward again to use it. Background operation still depends on iOS and usable location information.

Straightpoint and live ride announcements have their own controls and can work in the background without Background awareness. Turning Background awareness off doesn't stop either of them. Stop them with the **Straightpoint** switch or **End ride**.

### Mute speech

Select **Mute speech** near the start of Location to stop spoken app announcements. Select **Unmute speech** to hear them again. This includes location, ride, and Straightpoint speech, but doesn't mute VoiceOver.

Mute speech doesn't stop Straightpoint tones, ride sounds, or vibrations. Turn those off in their respective settings or ride options if you don't want them.

<h2 id="intersections">Exploring intersections</h2>

Select the **Intersections** tab to browse crossings along your current road. Rows include distance and compass direction when available. The closest crossing has a **Nearest intersection** prefix.

The list follows the road geographically rather than putting the closest crossing first. On a mainly north–south road, crossings to the north come before your position and crossings to the south come after it. On a mainly east–west road, it uses east and west. Turning your phone doesn't change that order.

### Follow a cross street

Select a cross-street row to browse that street around the same intersection. The road you just left appears at the current intersection. You can keep selecting cross streets to explore the surrounding streets without changing your real location.

**Reverse browse direction** reverses the browsing direction. **Return to my current street** brings you back to the road where you are now.

### Check crossing details

Choose **Open crossing details** from an intersection row's VoiceOver actions or **More** menu. You can do this from the Intersections list or from a populated Facing, Nearest, or Approaching intersection row on Location.

Details can include traffic control, pedestrian signals, accessible pedestrian signals, audible or vibrating indications, push buttons, tactile paving, kerbs, refuge islands, and crosswalks. The information comes from OpenStreetMap; the screen includes the data refresh date.

An approaching crossing may describe a cross street as left, right, ahead, or behind, relative to your travel direction. These descriptions help you understand the layout. They aren't instructions to cross. Missing mapped information means unknown, not absent, and the app doesn't tell you the current signal phase or when it's safe to cross.

<h2 id="places">Finding places and addresses</h2>

Select the **POIs** tab to browse nearby places or search for a business, category, address, or other destination. Selecting a result opens its details. You can also choose an action directly from the row.

### Search nearby

1. Choose **Nearby**, announced as **Search nearby** by VoiceOver.
2. Enter your search in **Search for a place**.
3. Press the keyboard's **Search** key.

Nearby search starts within two miles. **Expand search area to …** and **Reduce search area to …** change the area and repeat your search. The available distances are 2, 5, 10, 25, and 50 miles, shown in your chosen units. You can't reduce below the smallest area or expand beyond the largest.

The nearby list loads when you open the tab. **Refresh nearby places** or pull-to-refresh updates that list. To submit a search you've typed, press the keyboard's Search key.

### Search somewhere else

Choose **Anywhere**, announced as **Search anywhere** by VoiceOver, then enter a place or address and press **Search**. Include the city or region to help find the right place. **Repeat anywhere search** runs the search again.

Anywhere searches aren't limited to the nearby search area. Results for a distant city aren't ranked as though they're close to your phone. You can use them to start [virtual exploration](#virtual-walk).

### Read a place's location

A result can include its name, category, address, distance, and direction. **Southwest side of East 14th Street**, for example, describes the side of the street where the place is located. **Northeast** describes the direction from you to the place. The street side and the direction from you are different pieces of information.

Street-side information depends on the place's address and mapped road geometry. If it isn't shown, the app couldn't determine it. Place listings can be outdated, and the current Apple Maps source doesn't reliably identify closed businesses.

### Open maps or choose another action

A place's VoiceOver actions and **More** menu can include:

- **Open in maps**, to open the place in your chosen map app.
- **Walking directions**, to ask that map app for a route.
- **Watch with Straightpoint**, to select the place as your pointing target.
- **Explore virtually from here**, to explore the surrounding streets without going there.
- **Add to favorites**, to save the place. Saved places offer **Remove from favorites** instead.

Choose Apple Maps or Google Maps for map links in **Settings → General → Map provider**. This only changes which app opens places and directions. Straightforward's searches and nearby place information still come from Apple Maps in this iPhone beta.

<h2 id="favorites">Saving places</h2>

Favorites keep places you want to find again. You can save a business from search results or name the exact point where you're standing, such as a meeting spot.

### Save a listed place

1. Find the place on **POIs**.
2. Choose **Add to favorites** from its actions.
3. Open **POIs → View favorite places** to find it again.

A favorite offers map links, walking directions, Straightpoint, and an option to remove it. Favorites are stored on your phone. With a current position, the list shows the closest first and updates their distances. Without a position, it lists them alphabetically without a distance.

### Save where you're standing

1. Select the **Location** tab and wait for a current position.
2. With VoiceOver, focus **Location and awareness** and choose the **Save current location** action. Without VoiceOver, choose it from the heading's **More** menu.
3. In **Name this location**, check the accuracy information and enter a name in **Location name**.
4. Select **Save**, announced as **Save location** by VoiceOver.

The named location appears in **POIs → View favorite places**. The app saves the point captured when you chose Save current location, not a later position after you finish typing. Its precision depends on the phone's location accuracy. Map links use the saved coordinate rather than searching for a business with the name you entered.

<h2 id="straightpoint">Pointing toward a place with Straightpoint</h2>

Straightpoint gives feedback when your phone points toward a selected place. You can use it while standing still. It points along a straight line, so it won't guide you around a building or choose a safe walking route.

### Pick a place and turn it on

1. Find a place, favorite, or transit stop and choose **Watch with Straightpoint**.
2. Select **Location** and find the **Straightpoint** switch. The row shows the selected place and its distance and direction when available.
3. Turn **Straightpoint** on and complete any permission steps.
4. Turn your phone toward the place. You'll get feedback when it lines up; turning away stops the alignment feedback.

Choosing a place doesn't turn Straightpoint on if it's off. If it's already on, choosing another place starts guidance toward that place after any required permission check. You can also choose a target through [Ask Straightforward](#assistant).

Tones and vibrations become more frequent as you get closer, and the tones change pitch. Spoken feedback can give the place's name, straight-line distance, and compass direction. A separate **Near [place]** cue tells you you're close to its coordinate, which may be inside the building rather than at an entrance.

The distance on Location remains readable even with guidance off or the phone pointing away. If the app can't give you a current distance, it says so.

### Choose the feedback

Open **Settings → Straightpoint** to set **Guidance tones**, **Haptics** (vibrations), and **Announcements** separately. **Tone volume** changes the tones, not speech volume.

**Require level phone** is off by default. Turning it on limits feedback to when you hold the phone roughly level. Raising it upright pauses feedback; lowering it resumes when the sensors are ready. With the option off, you don't have to hold the phone level. This doesn't change the separate level-phone control used to move in virtual Auto mode.

Live Straightpoint can continue while locked or in another app with the required permission. It still needs usable location and sensor information, and iOS must allow it to run. Open the app again after force-quitting to use it.

### Pause or change your target

Turn **Straightpoint** off to stop feedback without losing the selected place. Turn it on again to continue.

Its Location row also offers **Open watched place in maps**, **Walking directions to watched place**, and **Clear Straightpoint watched place**. Clearing removes the place but doesn't change the switch. If the switch is on with **No watched place**, it waits until you choose one.

For a watched transit stop, **Open bus stop times** opens its details and departures.

<h2 id="transit">Transit stops and departures</h2>

Select the **Transit** tab to load nearby stops. Stop rows show the name, service direction, distance, routes, destinations, and near-side or far-side placement where available. Stops across the street can share a name, so choose the physical stop for the direction you want to travel.

**Near side** means before the cross street in the bus's direction of travel. **Far side** means after it. These descriptions refer to the bus's direction, not your walking direction. Placement is experimental and appears only when the available geometry supports it.

Select a stop to open its departures. **Refresh** or pull-to-refresh updates nearby stops or the stop details you're reading. Stop rows and detail headings also offer **Open in maps**, **Walking directions**, and **Watch with Straightpoint**. These use the selected stop's coordinate, not a search for another stop with the same name.

### Filter departures

1. Open a stop and read any service notices.
2. Select **Filter routes**.
3. Check the routes you want and select **Done**. Leaving all routes unchecked shows every route.
4. Select **Clear filters** to show all routes again.

**Load more departures** adds up to ten departures at a time, up to 100. Filters and the expanded list stay in place when you refresh or return from a trip. Stop details also refresh periodically while you're on that screen.

**Scheduled** means a timetable time. **Realtime** or **Predicted** means the app has a matching, current prediction. If one isn't available, the departure stays labeled as scheduled. **Feed updated** tells you when the source data changed, not when your phone last checked. Clock times use your phone's local time.

### See the stops on a trip

Select a departure to open **Stops on this trip**. It shows the selected stop and the stops after it for that particular journey. **Show previous stops** includes earlier stops; **Hide previous stops** hides them again. Select a stop to open its details.

The list follows that departure's trip and service day, rather than combining every branch of a route. On a loop, the same stop may appear more than once because the bus visits it more than once.

An arrival is only a prediction if there's a matching arrival update. **Scheduled arrival …, realtime arrival unavailable** is still a schedule. Skipped or canceled stops are marked as not boarding. Read any notices, and select **Open publisher notice** for the agency's full instructions when offered.

Transit supports operators in the United States, Canada, and Germany, but not every operator in those countries. Schedules, predictions, notices, placement, and live ride announcements can have different coverage. Seeing departures doesn't necessarily mean ride announcements are available for that trip.

<h2 id="ride">Stop announcements and get-off reminders</h2>

Ride watch follows your phone's position along a selected bus trip. It can announce each stop, remind you before your get-off stop, or do both. You choose the trip; the app doesn't identify your bus just because you're near it.

### Start a ride

1. On **Transit**, open a stop and find the departure for your route, direction, destination, and stopping pattern.
2. Choose **Start stop announcements** from the departure's actions. The same action is available after opening **Stops on this trip**.
3. Turn **Announce each stop** on to hear every stop, or leave it off for a get-off reminder only.
4. Select **Choose get-off stop** if you want a reminder, then choose the stop. You can also use a stop's **Get off here** action. On loops, choose the visit you intend to use.
5. Set **Speech**, **Sound**, and **Haptics** separately. These choices are saved. Read any special drop-off instructions.
6. Select **Start onboard**, complete any permission steps, and wait for the ride to start before locking the phone.

You can start before boarding or partway through the trip despite the Start onboard label. Once it starts, the app opens **Location**, where **Current ride** shows your progress.

A trip-stop row's **Notify me before this stop** action opens ride setup with that stop selected. Choosing a stop or opening setup doesn't start the watch; you still select Start onboard.

If Start isn't available, read the explanation. Ride watch needs the trip's path and passenger-stop information. Another departure with the same route number may follow a different branch or short turn and isn't necessarily a substitute.

### Follow your progress

The watch needs usable GPS fixes and movement to establish where you are along the trip. Waiting for the bus doesn't expire it simply because you haven't moved. Once it can track you, Current ride shows **Next stop** and remaining-stop information. **Tracking uncertain** means it can't confidently place you on the trip, for example during a GPS gap or on similar or repeated route sections.

Get-off reminders tell you when you're three stops away, when your stop is next, and when you're approaching it. Ordinary stop announcements and the three-stop reminder use the ordinary chime; the imminent get-off reminder has a distinct urgent cue. The app doesn't replay passed stops or missed reminder stages after a late start or GPS gap. Arrival predictions don't move the tracker forward; your position does.

A live ride can continue while locked or in another app after you've started it and allowed permission, subject to iOS and GPS availability. You don't need to turn on Background awareness or Straightpoint.

### End or resume a ride

Select **End ride** under **Location → Current ride** to stop tracking and cues and remove the saved ride. There isn't a Pause button for a running live ride, and an ended ride can't be resumed. Ending a ride doesn't clear your Straightpoint target.

After an interruption or a later launch, a saved ride may appear paused. Read its status and select **Resume**, announced as **Resume ride watch** by VoiceOver, if offered. Opening the app doesn't resume it automatically. You can select End ride instead. If cleanup doesn't finish, follow the retry message. A canceled or changed trip may need a new selection.

You can also start a ride by route name or change its get-off reminder through [Ask Straightforward](#assistant).

<h2 id="virtual-walk">Exploring streets virtually</h2>

Virtual mode lets you explore mapped streets without going there. It moves a simulated position while you stay where you are. Location, places, and intersections describe the virtual surroundings until you exit.

### Choose where to start

1. Open **POIs → Anywhere** and search for a place or address.
2. On the result you want, choose **Explore virtually from here**.
3. Select **Location** to find **Virtual mode: [place]** and the movement controls.

You can also start from a nearby place or another row that offers the same action.

### Move a step at a time

Select **Manual**, announced as **Manual mode** by VoiceOver. Adjust **Virtual step distance** with VoiceOver swipes up or down, or with **Less** and **More**. Choose a distance or **Next intersection**, then select a road-direction button to move that way.

Location updates for the new position. You can check the other tabs to explore nearby places and crossings. Directions follow connected mapped roads, rather than moving through buildings or across unmapped space.

### Move by pointing the phone

1. Select **Auto**, announced as **Auto mode** by VoiceOver.
2. Set **Virtual travel speed** to Slow walking, Normal walking, Fast walking, or Driving.
3. Face the phone toward an available road direction and hold it roughly level to move.
4. Raise the phone upright to pause.
5. At an intersection, Auto stops. Face another road to take it. To keep going in the original direction, raise the phone upright and lower it again.

Walking plays footsteps; Driving plays a continuous movement sound. There's a brief cue at intersections. A repeating blocked sound means there isn't a mapped continuation in that direction. Driving is a simulated speed, not a statement that driving is allowed on that road.

Leaving Location or switching away from the app pauses Auto. When you return, it needs usable heading and tilt information. Select Manual to stop Auto movement or Exit to finish exploring.

### Start over or return to your location

**Start over**, announced as **Return to virtual starting place** by VoiceOver, brings you back to the original virtual starting point.

You can choose **Watch with Straightpoint** while exploring, then turn on **Virtual Straightpoint** on Location. It points from your simulated position using the phone's facing direction. This temporary target doesn't replace your saved live target.

Select **Exit**, announced as **Exit virtual mode** by VoiceOver, to return to your real location. Previously active live features can be restored, so check their switches. A live ride suspended by virtual exploration stays paused until you explicitly Resume it. Walking-directions links are restricted while virtual so a map app doesn't unexpectedly route from your real location instead.

If **Waiting for road data** appears, give it time to load and try again. Missing data isn't the same as a dead end.

<h2 id="virtual-ride">Taking a virtual bus ride</h2>

A virtual bus ride follows a selected trip's path and stops. Unlike Auto street exploration, it doesn't follow the direction you point the phone.

1. On **Transit**, find a departure and choose **Explore this trip virtually**. You can also choose it after opening **Stops on this trip**.
2. Optionally select **Choose get-off stop** and choose a visit.
3. Set **Announce each stop**, **Speech**, **Sound**, and **Haptics**.
4. Select **Play virtual ride**.
5. On Location, find **Virtual bus ride** and use **Play**, **Pause**, **Next stop**, and **Virtual bus speed**. The speed choices are Slow, Normal, Fast, and Very fast.
6. Select **Exit virtual mode** when you're finished.

Playback starts at the stop where you looked up the departure. Next stop moves along the path to the next stop, then pauses. Stop announcements and get-off reminders use the same feedback as live rides.

Locking the phone or leaving the app pauses playback. Select Play after returning. A virtual ride doesn't test live GPS tracking. If you had a live ride running, entering virtual mode suspends it; it stays paused after exit until you Resume it.

<h2 id="assistant">Ask Straightforward</h2>

Ask Straightforward lets you request location information, find places, choose Straightpoint targets, and set up ride announcements in your own words.

It needs iOS 27, an Apple Intelligence-compatible iPhone, Apple Intelligence enabled, and Apple's system model downloaded and ready. These requirements apply to the assistant, not the ordinary tabs. If it isn't ready, the app explains why.

### Ask a question

1. Select **Ask Straightforward** above the tabs. You can also open it from the Location heading's actions.
2. Type your request or use iOS keyboard dictation.
3. Press **Return** or select **Send**.
4. Read the answer. With VoiceOver, focus moves to the completed reply without a second copy spoken by the app.
5. If it offers choices, select a numbered result button.

The assistant shows up to ten full results at a time. **Load more** continues the list; **Done with results** returns you to typing. While it needs a selection, the request field and Send are disabled, so choose a button rather than typing a number or another question. **No thanks** declines an offered wider search.

After it saves a target, you can type again without closing chat. Selecting a target doesn't turn Straightpoint on if it's off. Ask it to start Straightpoint separately.

Leaving chat cancels a running text request. Conversation history and still-valid choices can remain when you return, but aren't permanently saved. Scroll to read earlier messages. If an old result has expired, ask again. Text chat and Siri have separate conversations and result lists.

### Check your surroundings or find a target

Try requests such as:

- "What's my current address?" or "What's my street number?"
- "Which intersection am I facing?" or "What's my upcoming intersection?"
- "What's the nearest intersection?" or "What intersections are nearby?"
- "Find pizza nearby."
- "What transit stops are nearby?" or "What bus routes are nearby?"
- "Set Straightpoint to the nearest Starbucks."
- "Set Straightpoint on the southbound Bx9 stop at Broadway and Mosholu."
- "Set Straightpoint to 123 Main Street, Seattle."
- "Point at my saved hotel." or "Point to the facing intersection."
- "What's my Straightpoint target?"
- "Start Straightpoint," "Stop Straightpoint," or "Clear Straightpoint."

For a saved place, ask for the name you saved. There isn't a built-in Home address. If several saved places match, choose the right one from the results.

Say **Nearby** for a local search or **Anywhere** for a remote place or address. Anywhere doesn't provide worldwide transit search. If a nearby place search fails, the assistant may offer **Search Anywhere for this name**; you decide whether to widen it.

### Start a ride by route name

You don't have to open a departure first. For example:

- "Announce the stops on the Bx9 southbound."
- "Start announcements for the Bx9 southbound and tell me when we get to Broadway and Mosholu Avenue."
- "Tell me when we get to Broadway and Mosholu Avenue on the Bx9."

The last example asks for a get-off reminder without every-stop announcements. Choose the matching route, destination, and stopping pattern from the results. Route discovery is nearby. A compass direction helps narrow the request, but routes can bend, branch, or end early, so check the actual choices. If results are incomplete, you still need to make an explicit choice. The trip must support ride watch and have the necessary permission to start.

After a successful start, the app opens **Location → Current ride**. During that ride, you can say "Tell me when we get to Broadway and Mosholu Avenue" to add or change the reminder. Repeated or ambiguous stop names need a selection. "What is my ride status?" checks the ride, and "End ride" stops it.

### What the assistant handles

Apple's on-device model interprets requests. There's no automatic fallback to a cloud model, though place and transit searches still use online services. Siri recognition and keyboard dictation follow Apple's settings.

The assistant doesn't provide turn-by-turn walking navigation or tell you when it's safe to cross. It only controls supported app features, and has no custom wake word or always-listening microphone mode. Diagnostic exports can include location and search details; see [diagnostic logs](#diagnostics) before sharing one.

<h2 id="siri">Using Siri</h2>

1. Say **"Hey Siri, Ask Straightforward."**
2. Approve any first-use shortcut confirmation.
3. Wait for **"What would you like to ask Straightforward?"**
4. Say your request.

Keep the invocation and request separate. Combining them can send your question to Siri's own search instead.

Siri reads up to five choices at a time. Answer with a name, number, or distinguishing destination. Say **more** for another page or **done** to finish. "First one" means the first result on the current page. If Siri can't distinguish your answer, use more of the name or destination it read.

The conversation has a limited lifetime and number of follow-ups. If it expires, invoke Ask Straightforward again or use the in-app list. The shortcut opens the app to carry out the request without opening text chat. Siri handles its spoken replies; choices from a separate text conversation don't carry over.

<h2 id="settings">Voices, units, and other settings</h2>

Select the **Settings** tab, then choose **General**, **Location speech**, **Ride announcements**, **Straightpoint**, or **Diagnostics**. Changes are saved on your phone. If a change can't be saved, the app tells you.

### Distance units and maps

In **General → Distance units**, choose **Feet and miles** or **Meters and kilometers**. Feet and miles is the default. Changing units updates distances, search areas, virtual controls, and new assistant answers. It doesn't change the size of a search area or movement step, and earlier chat messages keep their original wording.

**Map provider** chooses Apple Maps or Google Maps for opening places and walking directions. It doesn't change where Straightforward gets search results or nearby place information.

### Location speech

1. Open **Location speech → Language** and choose a language, then a voice. **Voice** lets you change voices within that language. **System default** follows the system speech default.
2. Adjust **Speech rate**, **Pitch**, and **Volume**.
3. Select **Preview voice** to listen. Unmute app speech first if needed.

**Reload voices** updates the list of installed voices. **Reset speech settings** restores defaults. If your selected voice becomes unavailable, the app explains the fallback without discarding your saved choice. These controls don't change VoiceOver's voice.

**Keep hearing device audio connected** plays digital silence between announcements to help prevent a hearing device from cutting off the start of speech. It's off by default. It works while the app is open or user-started Background awareness is active, with app speech unmuted. It can use more battery and affect other audio. Try it with your hearing device and turn it off if it doesn't help.

### Ride voice

Ride announcements have their own voice, initially **System default**. Choose **Independent ride voice**, then **Ride language** and **Ride voice**. Or choose **Use location speech voice** to use that voice for rides too. This links the voice, not the location speech rate, pitch, or volume.

**Preview ride voice** lets you listen, and **Reload ride voices** updates the voice list. Choose Speech, Sound, Haptics, and whether to announce every stop when setting up the ride itself.

### Straightpoint settings

The Straightpoint page has **Guidance tones**, **Tone volume**, **Haptics**, **Announcements**, and **Require level phone**. See [Straightpoint](#straightpoint) for how these affect feedback.

<h2 id="internet">What needs an Internet connection?</h2>

Place searches, fresh road information, and transit lookups generally need a connection. Straightforward isn't a complete offline map or transit app.

Your favorites stay saved on the phone without Internet, but saving a place doesn't download the surrounding streets, businesses, or transit information. Straightpoint uses the selected coordinate and phone sensors for direction; finding a new place or refreshing its details can still need a connection.

A ride that's already started may keep tracking with its saved trip information and usable GPS. It can't learn about a new cancellation until it successfully checks for updates. Don't treat an old schedule as a current prediction.

The assistant interprets requests on the phone, but that doesn't make its online searches available offline. Siri and keyboard dictation have their own Apple system requirements.

<h2 id="diagnostics">Sending feedback and diagnostic logs</h2>

Email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com) with your build number, what you tried, and what happened. Include the exact control or message if you can. For incorrect transit placement, include the stop, route, service direction, and the missing or wrong near-side/far-side description.

### Share diagnostic logs

1. Reproduce the issue if practical, then open **Settings → Diagnostics**.
2. Select **Share diagnostic logs**.
3. Read the location-privacy explanation and select **Continue** if you want to share.
4. Choose a destination in the iOS share sheet, such as Messages or **Save to Files**.

If **Send diagnostic logs** is available, it opens an addressed email draft. Add a description and send it through Mail. If Mail won't send, close the draft and use Share diagnostic logs instead. Keep the logs until you've exported what you need.

Logs are kept locally with a size limit and can include precise real or virtual locations, searches, and target details. This export flow doesn't upload them automatically. You choose who receives the file and approve sending in the destination app. Don't post raw logs or personal travel details publicly.

**Clear local diagnostic logs** removes the retained logs and the app's export copy. It doesn't delete a report you've already sent or saved elsewhere. Exporting or canceling an export doesn't clear the logs.

<h2 id="troubleshooting">Troubleshooting</h2>

### Location or distances are unavailable

Check Straightforward's location permission and Precise Location in iPhone Settings, then return and select **Retry location**. GPS can be limited indoors or between buildings. The phone can have a position even if the address provider can't supply an address.

### Phone facing works, but Heading or Approaching intersection doesn't

Those fields need movement, not a compass turn. As you travel, give the app time to collect usable location fixes. You can check Nearest intersection or browse Intersections in the meantime.

### You can't hear announcements

Check **Unmute speech**, iPhone volume, and the audio device receiving sound. Try **Settings → Location speech → Preview voice**.

For Straightpoint, check its switch, selected place, alignment, feedback settings, Tone volume, and Require level phone option. For a ride, check Speech and Sound separately. VoiceOver and app speech have different volume controls.

### A search has no results

Check Nearby or Anywhere, then submit the search with the keyboard's **Search** key. You can expand a nearby search area. If the service is unavailable, check the connection and retry; that message doesn't mean there are no places or stops. You can use the ordinary tabs if an assistant search isn't completing.

### Road or crossing information is missing

**Some road data unavailable** means coverage is partial. **Waiting for road data** means the virtual road information hasn't loaded, not that you've reached a dead end. Wait and retry a Manual direction, or let Auto retry. OpenStreetMap crossing details are incomplete in many areas.

### A departure has no prediction or ride Start option

Scheduled departures aren't live tracking. Predictions need a matching current agency update, and ride watch needs additional trip-path and passenger-stop information. Check the selected departure and the app's explanation. Transit departures may still work even when live ride announcements aren't available.

### Current ride says Tracking uncertain

The watch is still running unless its status says paused or ended, but it can't confidently track your progress. A next-stop count that hasn't changed may be out of date. You can end the ride. If a restored ride is paused, select Resume when offered.

### Ask Straightforward isn't working

Read its readiness explanation. It needs the supported iOS version, eligible hardware, enabled Apple Intelligence, and a ready model. The ordinary tabs don't need that model. If the request field is disabled, finish the pending choices or select **Done with results**. If Siri searches the web instead, invoke Ask Straightforward first, wait for its prompt, then ask.

### Your controls differ from the guide

Check your installed build in TestFlight and whether a newer invited build is available. This guide describes build 30. If the app says a feature needs an updated client, reloading a screen won't add it.

[Return to contents](#contents)
