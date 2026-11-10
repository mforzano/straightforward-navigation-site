---
layout: default
title: User guide (draft)
description: How to use Straightforward on iPhone, including shared map pins, Nearby Explorer favorites import, location awareness, intersections, transit, virtual exploration, Straightpoint, and Siri.
permalink: /manual/
---

# Straightforward user guide

Draft for iPhone beta 0.1.0, build 31 · November 3, 2026

Straightforward puts your address, nearby places, intersections, and transit information together. You can check your surroundings, choose what gets announced as you move, or explore somewhere before you go there. Straightpoint helps you point your phone toward a place. It gives you the straight-line direction to your chosen place.

This guide describes build 31. If something is unclear or doesn't match what happens on your phone, email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com).

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
<li><a href="#import-favorites">Importing Nearby Explorer favorites</a></li>
<li><a href="#straightpoint">Pointing toward a place with Straightpoint</a></li>
<li><a href="#shared-location">Using a shared map pin</a></li>
<li><a href="#transit">Transit stops and departures</a></li>
<li><a href="#ride">Stop announcements and get-off reminders</a></li>
<li><a href="#virtual-walk">Exploring streets virtually</a></li>
<li><a href="#virtual-ride">Taking a virtual bus ride</a></li>
<li><a href="#assistant">Ask Straightforward</a></li>
<li><a href="#siri">Using Siri</a></li>
<li><a href="#settings">Voices, units, and other settings</a></li>
<li><a href="#internet">What needs an Internet connection?</a></li>
<li><a href="#privacy">Installation usage and privacy</a></li>
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

Select the **Location** tab to check your address, the direction you're moving, nearby intersections, and the nearest place. The information updates as your position changes.

The direction your phone points and the direction you're traveling are separate:

- **Phone facing** tells you where the phone points, using its compass. You can check this while standing still.
- **Heading** tells you which way you're moving. Turning the phone doesn't change your travel direction.

The intersection rows answer different questions:

- **Facing intersection** identifies an intersection in the direction your phone points, if one is available.
- **Nearest intersection** identifies the closest intersection, even if it's behind you.
- **Approaching intersection** identifies an intersection ahead along your direction of travel. It includes distance and available crossing information. The app needs enough movement to establish your travel direction before it can identify this intersection.

**Nearest POI** gives you a nearby place's name, with its category, distance, and direction where available. Its actions let you open it in maps, get walking directions, or select it for Straightpoint.

**Street** shows a nearby mapped road. **Near** appears when the road is farther from your position or location accuracy is uncertain. In virtual mode, **On** describes your simulated position.

At a crossing, **Street** can briefly show the cross street while **Approaching intersection** continues to follow your direction of travel.

**Street number** is Apple's estimate of a nearby address number. The other address fields also come from the location provider. **Street** shows the nearby mapped road separately.

When you're exploring virtually, Location describes your simulated position instead. [Virtual exploration](#virtual-walk) explains how to start and return to your real location.

<h2 id="announcements">Announcements and background awareness</h2>

Straightforward can announce changes as you move, so you don't have to keep checking the screen. Choose what you want to hear with the individual announcement switches. **Background awareness** lets those location announcements continue while your phone is locked or you're using another app.

### Choose your announcements

On the **Location** tab, turn on the switches for the information you want to hear, such as **Street**, **Street number**, **Heading**, **Approaching intersection**, or **Nearest POI**. Leave the others off. Your choices are saved.

All rows keep updating, including those with announcements off. **Phone facing**, **Facing intersection**, and **Nearest intersection** are available to read on the screen.

Approaching-intersection announcements tell you about the crossing at distance milestones rather than speaking every small change. Nearest POI announces when the nearest place changes, rather than repeating the same place as its distance changes.

### Keep location announcements going in the background

1. On **Location**, turn on **Background awareness**.
2. Complete the **Always** location permission steps if requested.
3. Check that the individual announcement switches you want are on.
4. Lock the phone or switch to another app.

Turn **Background awareness** off to stop background location awareness. Your individual announcement choices remain saved for the next time. The app also remembers the Background awareness choice and can restore it when you reopen the app, if permission is still available. After force-quitting, open Straightforward again to use it.

Straightpoint and live ride announcements use their own background controls. Stop them with the **Straightpoint** switch or **End ride**.

### Mute speech

Select **Mute speech** near the start of Location to stop spoken app announcements. Select **Unmute speech** to hear them again. This includes location, ride, and Straightpoint speech, but doesn't mute VoiceOver.

Control Straightpoint tones and vibrations in **Settings → Straightpoint**, and ride sounds and vibrations in the ride options.

<h2 id="intersections">Exploring intersections</h2>

Select the **Intersections** tab to browse crossings along your current road. Rows include distance and compass direction when available. In the live list, **Selected:** marks the nearest intersection. When browsing another street, it marks the intersection you used to enter that street instead.

The list follows the road geographically rather than putting the closest crossing first. On a mainly north–south road, crossings to the north come before your position and crossings to the south come after it. On a mainly east–west road, it uses east and west.

### Follow a cross street

1. Select a cross-street row to browse that street around the same intersection.
2. If several cross streets meet there, **Choose street** opens. Select **Browse [street name]** for the street you want. Use the native **Back** control to leave the chooser without selecting a street.
3. In the new street list, **Selected:** marks the same physical intersection, now labeled with the road you just left. With VoiceOver, focus moves to that row so you can continue from the same junction.

You can keep selecting cross streets to explore the surrounding streets without changing your real location. Use native **Back** to return through the streets you've browsed.

**Reverse browse direction** reverses the browsing direction. **Return to my current street** brings you back to the road where you are now.

Junction names can include an unnamed connection, such as **Broadway and unnamed service road**, **unnamed driveway**, or **unnamed footpath**. These labels describe the road or path type recorded in the map.

### Check crossing details

Choose **Open crossing details** from an intersection row's VoiceOver actions or **More** menu. You can do this from the Intersections list or from a populated Facing, Nearest, or Approaching intersection row on Location.

Details can include traffic control, pedestrian signals, accessible pedestrian signals, audible or vibrating indications, push buttons, tactile paving, kerbs, refuge islands, and crosswalks. The information comes from OpenStreetMap; the screen includes the data refresh date. Unlisted features have unknown status.

An approaching crossing may describe a cross street as left, right, ahead, or behind, relative to your travel direction. These descriptions help you understand the layout.

<h2 id="places">Finding places and addresses</h2>

Select the **POIs** tab to browse nearby places or search for a business, category, address, or other destination. Selecting a result opens its details. You can also choose an action directly from the row.

### Search nearby

1. Choose **Nearby**, announced as **Search nearby** by VoiceOver.
2. Enter your search in **Search for a place**.
3. Press the keyboard's **Search** key.

Nearby search starts within two miles. **Expand search area to …** and **Reduce search area to …** change the area and repeat your search. The available distances are 2, 5, 10, 25, and 50 miles, shown in your chosen units.

The nearby list loads when you open the tab. **Refresh nearby places** or pull-to-refresh updates that list. To submit a search you've typed, press the keyboard's Search key.

### Search somewhere else

Choose **Anywhere**, announced as **Search anywhere** by VoiceOver, then enter a place or address and press **Search**. Include the city or region to help find the right place. **Repeat anywhere search** runs the search again.

Use **Anywhere** to find a place in another city and start [virtual exploration](#virtual-walk).

### Read a place's location

A result can include its name, category, address, distance, and direction. **Southwest side of East 14th Street**, for example, describes the side of the street where the place is located. **Northeast** describes the direction from you to the place. The street side and the direction from you are different pieces of information.

Street-side descriptions use the place's address and mapped road geometry.

### Open maps or choose another action

A place's VoiceOver actions and **More** menu can include:

- **Open in maps**, to open the place in your chosen map app.
- **Walking directions**, to ask that map app for a route.
- **Watch with Straightpoint**, to select the place as your pointing target.
- **Explore virtually from here**, to explore the surrounding streets without going there.
- **Add to favorites**, to save the place. Saved places offer **Remove from favorites** instead.

In **Settings → General → Map provider**, choose Apple Maps or Google Maps for opening places and walking routes. Straightforward uses Apple Maps for place searches.

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

The named location appears in **POIs → View favorite places**. The app saves your position when you choose **Save current location**. Map links open that saved coordinate.

### Delete several favorites

1. Open **POIs → View favorite places**, then select **Edit** in the navigation header.
2. Select a favorite row to check it; select it again to uncheck it. In this mode, rows select favorites rather than opening their details. VoiceOver reads the checkbox state and confirms **Selected [name]** or **Deselected [name]**.
3. To select the whole list, including favorites not currently onscreen, choose **Select All**. **Deselect All** clears the selection. VoiceOver confirms the bulk selection, and the toolbar shows the selected count.
4. Select **Delete N favorites**. Read the count in the confirmation, then select its **Delete N favorites** action to remove those favorites, or **Cancel** to keep them. Delete is unavailable when nothing is selected. Deletion can't be undone.
5. Select **Done** to leave selection mode and return to ordinary place details and actions. Done clears the selection.

<h3 id="import-favorites">Import Nearby Explorer favorites</h3>

Bring a Nearby Explorer favorites export into Straightforward without replacing your existing favorites.

1. Save the Nearby Explorer **.nefavs** export in the iPhone **Files** app or an available Files provider such as iCloud Drive.
2. In Straightforward, open **Settings → Favorites → Import Nearby Explorer favorites**.
3. Select **Choose export from Files**, then choose the export.
4. Read the preview: it gives the record count, valid favorites, invalid records skipped, already-imported records, new favorites to add, and provider ID conflicts. Different records with the same provider ID are kept separately. Unsupported metadata fields are counted but not imported.
5. Select **Import N favorites** to save the new favorites. Choose **Cancel import** or **Back** before confirming to cancel.
6. After the success message, open **POIs → View favorite places**. Select a favorite for its details, including notes, accessibility notes, website, and floor when present. Native **Back** from the import screen returns to Favorites settings; Back again returns to Settings.

Choose a Nearby Explorer **.nefavs** export, up to 8 MB and 20,000 records. The app previews the file before importing it locally. It keeps the original file intact and retains names, coordinates, addresses, categories, phone numbers, websites, and notes.

Reimporting skips unchanged records and preserves your existing favorites and edits. Changed source records are added as separate favorites. Reimporting can restore an imported favorite you've deleted.

For imported named places, **Open in maps** searches your chosen map provider using the saved name and available address, with the coordinate as location context. It may offer several matches or no match. **Walking directions**, Straightpoint, and virtual starting points use the stored destination coordinate. Personal **Save current location** bookmarks continue to open as coordinate pins, not business-name searches.

<h2 id="straightpoint">Pointing toward a place with Straightpoint</h2>

Straightpoint gives feedback when your phone points toward a selected place. You can use it while standing still.

### Pick a place and turn it on

1. Find a place, favorite, or transit stop and choose **Watch with Straightpoint**.
2. Select **Location** and find the **Straightpoint** switch. The row shows the selected place and its distance and direction when available.
3. Turn **Straightpoint** on and complete any permission steps.
4. Turn your phone toward the place. You'll get feedback when it lines up; turning away stops the alignment feedback.

If Straightpoint is already on, choosing another place updates the guidance after any required permission check. You can also choose a target through [Ask Straightforward](#assistant).

Tones and vibrations become more frequent as you get closer, and the tones change pitch. Spoken feedback can give the place's name, straight-line distance, and compass direction. A separate **Near [place]** cue tells you you're close to the selected coordinate.

The distance on Location remains readable even with guidance off or the phone pointing away.

The target can include a street-side description alongside its direction from you. **Loading street side**, **Street side temporarily unavailable**, and **Street side could not be determined** report the street-side lookup status. Straightpoint's pointing feedback works separately.

### Choose the feedback

Open **Settings → Straightpoint** to set **Guidance tones**, **Haptics** (vibrations), and **Announcements** separately. **Tone volume** changes the tones, not speech volume.

**Require level phone** is off by default. Turning it on limits feedback to when you hold the phone roughly level. Raising it upright pauses feedback; lowering it resumes when the sensors are ready. With this option off, Straightpoint works with the phone upright or level.

Live Straightpoint can continue while locked or in another app with the required permission. Open the app again after force-quitting to use it.

### Pause or change your target

Turn **Straightpoint** off to stop feedback without losing the selected place. Turn it on again to continue.

Its Location row also offers **Open watched place in maps**, **Walking directions to watched place**, and **Clear Straightpoint watched place**. Clearing removes the place but doesn't change the switch. If the switch is on with **No watched place**, it waits until you choose one.

For a watched transit stop, **Open bus stop times** opens its details and departures.

<h3 id="shared-location">Use a shared map pin</h3>

You can send a static destination pin from Maps to Straightforward and use it as a Straightpoint target. For example, someone can send a meeting point in Messages without having Straightforward themselves.

1. In **Apple Maps**, select the destination or drop a pin at the intended stationary location. If someone sent you a location card in Messages, open that pin in Maps first.
2. Choose **Share**, then **Straightforward**. If it isn't listed, check the share sheet's **More** list.
3. On **Shared location**, review the static pin and its name. Edit **Pin name** if you want another label. Latitude and longitude appear in the preview.
4. Select **Set Straightpoint** to replace the selected target. If Straightpoint is on, guidance updates to the new pin. Otherwise, turn it on from **Location** when you want guidance.
5. To leave without changing the old target, choose **Cancel** or native **Back** before confirming.

The pin marks a fixed destination. If the meeting point changes, ask for a fresh pin.

Share a static destination pin from Apple Maps or a Google Maps pin with explicit coordinates. If the app can't read the link, open Maps, drop a pin at the destination, and share that pin. If it still fails, send feedback.

<h2 id="transit">Transit stops and departures</h2>

Select the **Transit** tab to load nearby stops. Stop rows show the name, service direction, distance, routes, destinations, and near-side or far-side placement where available. Stops across the street can share a name, so choose the physical stop for the direction you want to travel.

**Near side** means before the cross street in the bus's direction of travel. **Far side** means after it. These descriptions refer to the bus's direction, not your walking direction. Near-side and far-side descriptions appear when the stop and road data support them.

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

Transit covers selected operators in the United States, Canada, and Germany. Each stop shows its available departures, predictions, notices, and placement details. Use **Start stop announcements** on a supported departure to set up a ride.

<h2 id="ride">Stop announcements and get-off reminders</h2>

Ride watch follows your phone's position along a selected bus trip. It can announce each stop, remind you before your get-off stop, or do both. Choose your trip from its departures to start.

### Start a ride

1. On **Transit**, open a stop and find the departure for your route, direction, destination, and stopping pattern.
2. Choose **Start stop announcements** from the departure's actions. The same action is available after opening **Stops on this trip**.
3. Turn **Announce each stop** on to hear every stop, or leave it off for a get-off reminder only.
4. Select **Choose get-off stop** if you want a reminder, then choose the stop. You can also use a stop's **Get off here** action. On loops, choose the visit you intend to use.
5. Set **Speech**, **Sound**, and **Haptics** separately. These choices are saved. Read any special drop-off instructions.
6. Select **Start onboard**, complete any permission steps, and wait for the ride to start before locking the phone.

You can start before boarding or partway through the trip despite the Start onboard label. Once it starts, the app opens **Location**, where **Current ride** shows your progress.

A trip-stop row's **Notify me before this stop** action opens ride setup with that stop selected. Select **Start onboard** when you're ready to begin the watch.

If Start is unavailable, read the explanation. When choosing another departure, check its destination and stopping pattern.

### Follow your progress

The watch needs usable GPS fixes and movement to establish where you are along the trip. Once it can track you, Current ride shows **Next stop** and remaining-stop information. **Tracking uncertain** means it can't confidently place you on the trip, for example during a GPS gap or on similar or repeated route sections.

Get-off reminders tell you when you're three stops away, when your stop is next, and when you're approaching it. Ordinary stop announcements and the three-stop reminder use the ordinary chime; the imminent get-off reminder has a distinct urgent cue. The app doesn't replay passed stops or missed reminder stages after a late start or GPS gap. Arrival predictions don't move the tracker forward; your position does.

After you start a ride and allow permission, it can continue while your phone is locked or you're using another app.

### End or resume a ride

Select **End ride** under **Location → Current ride** to stop tracking and cues and remove the saved ride. To ride again after ending, start a new watch. Your Straightpoint target stays selected.

After an interruption or a later launch, a saved ride may appear paused. Read its status and select **Resume**, announced as **Resume ride watch** by VoiceOver, if offered. You can select End ride instead. If cleanup doesn't finish, follow the retry message. A canceled or changed trip may need a new selection.

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

Walking plays footsteps; Driving plays a continuous movement sound. There's a brief cue at intersections. A repeating blocked sound means there isn't a mapped continuation in that direction.

Leaving Location or switching away from the app pauses Auto. When you return, it needs usable heading and tilt information. Select Manual to stop Auto movement or Exit to finish exploring.

### Start over or return to your location

**Start over**, announced as **Return to virtual starting place** by VoiceOver, brings you back to the original virtual starting point.

You can choose **Watch with Straightpoint** while exploring, then turn on **Virtual Straightpoint** on Location. It points from your simulated position using the phone's facing direction. This temporary target doesn't replace your saved live target.

Select **Exit**, announced as **Exit virtual mode** by VoiceOver, to return to your real location. Previously active live features can be restored, so check their switches. A live ride suspended by virtual exploration stays paused until you explicitly Resume it. Exit virtual mode before requesting walking directions.

If **Waiting for road data** appears, give it time to load and try again.

<h2 id="virtual-ride">Taking a virtual bus ride</h2>

A virtual bus ride follows a selected trip's path and stops. Unlike Auto street exploration, it doesn't follow the direction you point the phone.

1. On **Transit**, find a departure and choose **Explore this trip virtually**. You can also choose it after opening **Stops on this trip**.
2. Optionally select **Choose get-off stop** and choose a visit.
3. Set **Announce each stop**, **Speech**, **Sound**, and **Haptics**.
4. Select **Play virtual ride**.
5. On Location, find **Virtual bus ride** and use **Play**, **Pause**, **Next stop**, and **Virtual bus speed**. The speed choices are Slow, Normal, Fast, and Very fast.
6. Select **Exit virtual mode** when you're finished.

Playback starts at the stop where you looked up the departure. Next stop moves along the path to the next stop, then pauses. Stop announcements and get-off reminders use the same feedback as live rides.

Locking the phone or leaving the app pauses playback. Select Play after returning. If you had a live ride running, entering virtual mode suspends it; it stays paused after exit until you Resume it.

<h2 id="assistant">Ask Straightforward</h2>

Ask Straightforward lets you request location information, find places, choose Straightpoint targets, and set up ride announcements in your own words.

It needs iOS 27, an Apple Intelligence-compatible iPhone, Apple Intelligence enabled, and Apple's system model downloaded and ready. These requirements apply to the assistant, not the ordinary tabs. If it isn't ready, the app explains why.

### Ask a question

1. Select **Ask Straightforward** above the tabs. You can also open it from the Location heading's actions.
2. Type your request or use iOS keyboard dictation.
3. Press **Return** or select **Send**.
4. Read the answer. With VoiceOver, focus moves to the completed reply.
5. If it offers choices, select a numbered result button.

The assistant shows up to ten full results at a time. **Load more** continues the list; **Done with results** returns you to typing. While it needs a selection, the request field and Send are disabled, so choose a button rather than typing a number or another question. **No thanks** declines an offered wider search.

After it saves a target, you can type again without closing chat. Ask it to start Straightpoint when you're ready for guidance.

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

For a saved place, ask for the name you saved. To use Home, save your home as a favorite named Home. If several saved places match, choose the right one from the results.

Say **Nearby** for a local search or **Anywhere** for a remote place or address. Transit searches use your nearby area. If a nearby place search fails, the assistant may offer **Search Anywhere for this name**; you decide whether to widen it.

### Start a ride by route name

You don't have to open a departure first. For example:

- "Announce the stops on the Bx9 southbound."
- "Start announcements for the Bx9 southbound and tell me when we get to Broadway and Mosholu Avenue."
- "Tell me when we get to Broadway and Mosholu Avenue on the Bx9."

The last example asks for a get-off reminder without every-stop announcements. Route discovery is nearby. Include the direction to narrow your request, then select the matching route, destination, and stopping pattern from the results. Complete any permission steps to start.

After a successful start, the app opens **Location → Current ride**. During that ride, you can say "Tell me when we get to Broadway and Mosholu Avenue" to add or change the reminder. Repeated or ambiguous stop names need a selection. "What is my ride status?" checks the ride, and "End ride" stops it.

### What the assistant handles

Apple's on-device model interprets requests. Place and transit searches use online services. Siri recognition and keyboard dictation follow Apple's settings.

<h2 id="siri">Using Siri</h2>

1. Say **"Hey Siri, Ask Straightforward."**
2. Approve any first-use shortcut confirmation.
3. Wait for **"What would you like to ask Straightforward?"**
4. Say your request.

Keep the invocation and request separate. Combining them can send your question to Siri's own search instead.

Siri reads up to five choices at a time. Answer with a name, number, or distinguishing destination. Say **more** for another page or **done** to finish. "First one" means the first result on the current page. If Siri can't distinguish your answer, use more of the name or destination it read.

The conversation has a limited lifetime and number of follow-ups. If it expires, invoke Ask Straightforward again or use the in-app list. The shortcut opens the app to carry out the request without opening text chat. Siri handles its spoken replies; choices from a separate text conversation don't carry over.

<h2 id="settings">Voices, units, and other settings</h2>

Select the **Settings** tab, then choose **General**, **Location speech**, **Ride announcements**, **Straightpoint**, **Favorites**, or **Diagnostics**. Favorites contains [Import Nearby Explorer favorites](#import-favorites). Changes are saved on your phone.

### Distance units and maps

In **General → Distance units**, choose **Feet and miles** or **Meters and kilometers**. Feet and miles is the default. Changing units updates distances, search areas, virtual controls, and new assistant answers. It doesn't change the size of a search area or movement step, and earlier chat messages keep their original wording.

**Map provider** chooses Apple Maps or Google Maps for opening places and walking directions.

### Location speech

1. Open **Location speech → Language** and choose a language, then a voice. **Voice** lets you change voices within that language. **System default** follows the system speech default.
2. Adjust **Speech rate**, **Pitch**, and **Volume**.
3. Select **Preview voice** to listen. Unmute app speech first if needed.

**Reload voices** updates the list of installed voices. **Reset speech settings** restores defaults. If your selected voice becomes unavailable, the app explains the fallback without discarding your saved choice.

**Keep hearing device audio connected** plays digital silence between announcements to help prevent a hearing device from cutting off the start of speech. It's off by default. It works while the app is open or user-started Background awareness is active, with app speech unmuted. Try it with your hearing device and turn it off if it doesn't help.

### Ride voice

Ride announcements have their own voice, initially **System default**. Choose **Independent ride voice**, then **Ride language** and **Ride voice**. Or choose **Use location speech voice** to use that voice for rides too. This links the voice, not the location speech rate, pitch, or volume.

**Preview ride voice** lets you listen, and **Reload ride voices** updates the voice list. Choose Speech, Sound, Haptics, and whether to announce every stop when setting up the ride itself.

### Straightpoint settings

The Straightpoint page has **Guidance tones**, **Tone volume**, **Haptics**, **Announcements**, and **Require level phone**. See [Straightpoint](#straightpoint) for how these affect feedback.

<h2 id="internet">What needs an Internet connection?</h2>

Place searches, fresh road information, and transit lookups generally need a connection.

Favorites stay saved on your phone offline. Straightpoint uses the selected coordinate and phone sensors for direction.

A ride that's already started may keep tracking with its saved trip information and usable GPS. Reconnect to receive cancellations and other service updates.

Mapped road coverage includes the United States, Canada, and Germany. Road connections and crossing details come from the available mapped data. Road coverage and transit coverage are separate.

<h2 id="privacy">Installation usage and privacy</h2>

Requests to Straightforward's road and transit services can include a random identifier saved for this installation, the app version and build, and whether the app is in the foreground or background. This helps measure active installations and service failures.

The separate usage-metrics records store a digest of that random identifier, hourly service counts and outcomes, and coarse app metadata for up to 90 days. They don't include coordinates, searches, favorite names, email addresses, or device fingerprints, and aren't joined to operational access logs. The identifier isn't sent to Apple or Google Maps. These limited service metrics are separate from the local diagnostic logs you explicitly export below.

<h2 id="diagnostics">Sending feedback and diagnostic logs</h2>

Email [contact@straightforwardnavigation.com](mailto:contact@straightforwardnavigation.com) with your build number, what you tried, and what happened. Include the exact control or message if you can. For incorrect transit placement, include the stop, route, service direction, and the missing or wrong near-side/far-side description.

### Share diagnostic logs

1. Reproduce the issue if practical, then open **Settings → Diagnostics**.
2. Select **Share diagnostic logs**.
3. Read the location-privacy explanation and select **Continue** if you want to share.
4. Choose a destination in the iOS share sheet, such as Messages or **Save to Files**.

If **Send diagnostic logs** is available, it opens an addressed email draft. Add a description and send it through Mail. If Mail won't send, close the draft and use Share diagnostic logs instead. Keep the logs until you've exported what you need.

Logs are kept locally with a size limit and can include precise real or virtual locations, searches, and target details. This export flow doesn't upload them automatically. You choose who receives the file and approve sending in the destination app.

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

Check your installed build in TestFlight and whether a newer invited build is available. This guide describes build 31. If a feature asks for an updated client, install the newer invited build in TestFlight.

[Return to contents](#contents)
