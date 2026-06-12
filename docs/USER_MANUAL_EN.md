# User Manual – Bike Route Planner

## Product Overview

**Bike Route Planner** (**BRP**) is an Android application for cyclists that helps you plan routes and provides navigation instructions during your ride. The app is designed to help you reach your destination safely, clearly, and efficiently.

### Who is the app for?

The app is suitable for different types of cyclists:

* **Road cyclists** – riders looking for smooth routes on paved surfaces.
* **Gravel riders** – riders who want to combine asphalt, gravel, and lightly unpaved roads.
* **MTB riders** – riders who prefer forest roads, trails, and off-road sections.
* **Commuters** – riders who regularly travel to work, school, or around the city.
* **Touring cyclists** – riders planning longer trips at a steady pace.
* **Explorers** – riders who want to discover new routes and less familiar sections.

### Key Benefits

* **Offline routing** – no internet connection is required during the ride.
* **Custom route planning** – create routes based on your own preferences.
* **Overlay navigation** – routes from BRP can be displayed in Bike Radar Overlay.
* **Multiple bike types** – route calculation adapts to the selected bike type.
* **Multiple route styles** – choose a faster, shorter, safer, or balanced route.
* **Loop routes** – the app can generate round trips based on a selected distance.

---

## Installation and Requirements

### Device Requirements

* **Android 8.0** / **API 26** or newer
* **GPS sensor** for location tracking
* **Free storage space** for map data

### Installing BRouter

BRP requires the **BRouter** app to work correctly. BRouter is used for offline route calculation.

#### How to install BRouter

1. Open BRP. On first launch, a dialog will appear with an option to download BRouter.
2. Go to the Google Play Store and install **BRouter**.
3. After installation, open BRouter and download map data for the area where you want to plan routes.

### Installing Bike Radar Overlay

Installing **Bike Radar Overlay** is optional.

If you want to display navigation instructions in overlay mode, for example on the lock screen or in a riding display, install **Bike Radar Overlay** as well.

Bike Radar Overlay is used to display information during the ride and can also show navigation instructions from BRP.

---

## Introduction to Route Planning

### How to start

1. Launch **Bike Route Planner**.
2. On the main screen, tap **Planner**.
3. Select the start point and destination of the route.

### Selecting the start point

* **Use GPS**: Tap the location icon in the top-right corner. The app will use your current location.
* **Select on map**: Tap and hold the place on the map where the route should start.

### Selecting the destination

* **Select on map**: Tap and hold the place on the map where the route should end.
* **Cancel destination**: You can cancel the destination by tapping the **X** icon in the top-right corner.

### Adding via points

Via points are used to make the route pass through specific places.

1. After selecting the destination, tap the **+** button.
2. Tap and hold the desired place on the map.
3. A new via point will be added.

You can add up to **8 via points**.

---

## Bike Types

The app supports 6 bike types. Each type uses different route profiling.

### 1. Road – Road Bike

**Description:**
A road profile focused on paved surfaces, smooth riding, and safety.

**Prefers:**

* asphalt and concrete surfaces,
* cycle paths and cycling routes,
* residential areas with lower traffic speed.

**Avoids:**

* unpaved off-road tracks,
* poor-quality surfaces,
* technically difficult sections.

**Recommended for:**
Road bike riders who want a smooth and safe ride on good-quality surfaces.

### 2. Gravel – Gravel Bike

**Description:**
A profile combining asphalt, gravel, and well-rideable unpaved roads.

**Prefers:**

* asphalt and paved surfaces,
* fine gravel,
* good-quality forest and field roads.

**Tolerates:**

* medium-quality unpaved roads,
* roads tagged as `tracktype grade 1–3`.

**Avoids:**

* poorly rideable surfaces,
* highly technical sections.

**Recommended for:**
Gravel riders who want a mix of road and light off-road riding.

### 3. MTB – Mountain Bike

**Description:**
A profile for off-road riding, trails, and more technical sections.

**Prefers:**

* off-road routes and trails,
* forest and park paths,
* roads tagged as `tracktype grade 1–3`.

**Tolerates:**

* unpaved surfaces,
* footpaths where cycling is allowed,
* good-quality hiking paths.

**Avoids:**

* motor-vehicle roads where bicycles are not allowed,
* roads with clear access restrictions.

**Recommended for:**
MTB riders who want to ride off-road.

### 4. Touring – Touring Bike

**Description:**
A profile for longer rides at a steady pace and on reliable surfaces.

**Prefers:**

* reliable surfaces,
* routes with a smooth pace,
* longer routes suitable for comfortable riding.

**Tolerates:**

* medium-quality unpaved roads,
* calmer roads with lower traffic speeds.

**Recommended for:**
Touring cyclists who want longer and more comfortable routes.

### 5. Commute – Commuter Bike

**Description:**
A profile for everyday transport with emphasis on reliability, clarity, and time.

**Prefers:**

* firm surfaces,
* direct routes,
* familiar and reliable roads.

**Tolerates:**

* cycle paths,
* residential areas,
* urban roads suitable for bicycles.

**Recommended for:**
Daily rides to work, school, or around the city.

### 6. Explore – Exploration Profile

**Description:**
A profile for discovering new routes and less familiar sections, even at the cost of lower predictability.

**Prefers:**

* new and less familiar routes,
* a mix of different surfaces,
* discovering new places.

**Tolerates:**

* more risky sections,
* less predictable routes,
* greater surface variety.

**Recommended for:**
Riders who want to discover new routes and do not mind a higher level of uncertainty.

---

## Route Styles

The route style determines how the app balances safety, speed, distance, and comfort.

### 1. Faster – Faster Route

**Description:**
A faster profile that gives higher priority to travel time. It may use busier roads if cycling is allowed there.

**What it does:**

* prioritizes speed and efficiency,
* may accept roads with heavier traffic,
* selects a faster option even if it is less calm.

**Notice:**
This style may route you along roads with heavier traffic. Sections where cycling is prohibited remain excluded.

**Use case:**
Suitable when you need to reach your destination as quickly as possible and do not mind riding on less quiet roads.

### 2. Shortest – Shortest Route

**Description:**
A profile focused on minimizing total route distance. It may include less comfortable or busier sections if cycling is legally allowed there.

**What it does:**

* minimizes total route length,
* may choose shorter but less comfortable roads,
* may use roads with heavier traffic.

**Notice:**
The shortest route is not always the most comfortable or the safest option.

**Use case:**
Suitable when you want the shortest possible route regardless of comfort.

### 3. Touring / Balanced – Balanced Route

**Description:**
A balanced profile for regular rides and longer trips.

**What it does:**

* balances speed, safety, and surface quality,
* accepts moderately busy roads,
* prefers good-quality and reliable surfaces.

**Use case:**
Recommended as the default option for most users.

### 4. Safer – Safer Route

**Description:**
A profile with a stronger preference for calm sections, cycle paths, and roads with lower traffic.

**What it does:**

* prioritizes safer routes,
* strongly penalizes main roads without bike lanes,
* prefers cycle paths, residential areas, and quiet roads.

**Use case:**
Suitable if you prefer a calmer ride and are willing to take a longer route in exchange for higher safety.

---

## Main Interface Overview

### Main Screen

```text id="8eifnj"
+---------------------------------+
| [Menu]              [Planner]   |
|                                 |
|   [Map with route]              |
|                                 |
| [Start ride]                    |
| [Continue planning]             |
| [Back to menu]                  |
+---------------------------------+
```

### Menu

Tap the menu icon in the bottom-left corner to open the side menu with additional functions:

* **Map planner** – return to route planning.
* **Edit UI** – adjust interface size and appearance.
* **Offline data** – manage BRouter map data.
* **App settings** – language, surface display, traffic display, and other options.
* **Exit** – close the app.

---

## Detailed Feature Guide

## Chapter 1: Selecting Start and Destination

### Selecting the start point using GPS

1. Tap **Planner**.
2. Wait until the app obtains your GPS location.
3. Once the location icon turns green, the position is ready to use.

### Selecting the start point from the map

1. Tap **Planner**.
2. Tap and hold the place on the map where the route should start.
3. After a moment, a confirmation dialog will appear.
4. Confirm the selection.

### Selecting the destination from the map

1. After selecting the start point, the **To** button will appear.
2. Tap and hold the place on the map where the destination should be.
3. After a moment, a confirmation dialog will appear.
4. Confirm the selection.

### Editing the start point or destination

* You can move the selected start point or destination on the map.
* Tap and hold the point, then move it to a new location.
* Confirm the new position.

### Removing a point

* Tap the **X** icon next to the point.
* Confirm removal.

---

## Chapter 2: Via Points

### Adding a via point

1. After selecting the destination, tap the **+** button.
2. Tap and hold the place on the map where the via point should be.
3. Confirm the selection.

### Point order

* The start point is always first.
* The destination is always last.
* Via points are ordered according to the order in which they were added.

### Changing the order

* The order of via points currently cannot be changed.
* If you need a different order, create a new route.

### Removing a via point

1. Tap **Clear**.
2. Select the point you want to remove.
3. Confirm removal.

---

## Chapter 3: Generating a Loop Route

### How to generate a loop

1. Tap **Loop**.
2. Select the starting location using GPS or by selecting a point on the map.
3. Set the target distance:

   * minimum: **5 km**,
   * recommended: **30 km**,
   * maximum: **150 km**.
4. Select the number of loop points:

   * minimum: **3 points**,
   * recommended: **6 points**,
   * maximum: **9 points**.
5. Select the preferred direction: **N, NE, E, SE, S, SW, W, NW**.
6. Select the riding direction: **clockwise** or **counterclockwise**.
7. Tap **Generate loop**.

### Editing the loop

* After the loop is generated, you can adjust its points directly on the map.
* Tap **Edit loop** to enter editing mode.
* Tap **Regenerate** to create a new calculation.

### Deleting the loop

* Tap **Clear loop**.
* The loop will be removed, but the map will remain displayed.

---

## Chapter 4: Starting Navigation

### Starting navigation

1. After finishing route planning, tap **Go**.
2. The app will start processing the route.
3. Once the calculation is complete, tap **Go** again to start navigation.

### During navigation

* The app continuously displays navigation status.
* It shows instructions for the next turn.
* The distance to the next turn is updated continuously.

### Pausing navigation

* Tap **Pause**.
* Navigation instructions are not shown while paused.
* Location tracking continues.

### Resuming after pause

* Tap **Resume**.
* Navigation continues from the current or last known location.

### Route recalculation

If you leave the planned route, the app automatically recalculates it.

* A new route is calculated from your current location.
* Recalculation usually takes a few seconds.

### Ending navigation

1. Tap **Cancel**.
2. Confirm that you want to end navigation.
3. The map remains displayed, but navigation stops.

---

## Chapter 5: App Settings

### App language

* **System** – uses the device language.
* **English** – English.
* **Čeština** – Czech.

### Navigation language

Navigation language controls the language of navigation instructions and names.

The available options are the same as for the app language.

### Default map zoom

* Sets the default map zoom level.
* The range is from **3** to **19**.
* The recommended value is **14**.

### Display cycling routes

* Shows highlighted cycling routes on the map.
* Helps identify official or marked cycling routes.
* Transparency can be adjusted between **25–75%**.

### Display walking routes

* Shows hiking and walking routes on the map.
* Helps with planning routes in nature or outside cities.
* Transparency can be adjusted between **25–75%**.

### Navigation display settings

* **Minimum zoom** – used for more distant turns.
* **Maximum zoom** – used for nearby turns.

### Custom route style

* **Line width** – adjustable from **2–18**.
* **Line color** – selectable from the available palette.

### Interface customization

* **Button size** – adjustable from **85–145%**.
* **Control size** – affects the size of map controls.
* **Rider icon size** – adjustable from **20–44 dp**.
* **Navigation banner size** – adjusts the size of the text and arrow.

---

## Chapter 6: Offline Data for BRouter

### How to download map data

1. In the menu, tap **Offline data**.
2. Information about BRouter will be displayed.
3. Tap **Open download manager**.
4. In BRouter, select the desired area.
5. Download the segments for the area where you want to plan routes.

### Checking data availability

* The app automatically checks whether the required segments are downloaded.
* If any are missing, a warning is displayed.
* Recommended segments are highlighted.

### Recalculating recommended segments

* After changing the start point or destination, the recommended segments are recalculated.
* Tap **Refresh** to start a new calculation.

---

## Chapter 7: Bike Radar Overlay Integration

### How to set up the integration

1. Install **Bike Radar Overlay**.
2. Launch Bike Radar Overlay and complete the basic setup.
3. Plan a route in BRP and start navigation.
4. Navigation data will be sent to Bike Radar Overlay.

### What is sent to Bike Radar Overlay

* **Distance to turn** – in meters.
* **Turn type** – for example “Right”, “Left”, etc.
* **Street name** – the name of the road you are riding on.
* **Time to destination** – estimated arrival time.
* **Navigation status** – for example active navigation, riding, or GPS loss.

### Display in Bike Radar Overlay

* Bike Radar Overlay can display navigation on the lock screen or in riding mode.
* If the next turn is closer than **200 m**, the display may turn on.
* Radar alerts have higher priority than navigation instructions.

---

## Chapter 8: Route Explanation

### Why did the app choose a specific route?

The app can display a route summary that helps explain why the route was calculated in a particular way.

The summary may include:

* **Distance** – total route distance.
* **Duration** – estimated riding time.
* **Surface** – percentage distribution of surface types, such as asphalt or gravel.
* **Traffic** – share of sections with different traffic levels.
* **Risks** – number of problematic sections, such as sharp turns or U-turns.

### More problematic sections

The app marks problematic sections in orange.

These may include:

* **possible U-turns**,
* **sharp direction reversals**,
* **returning along the same road**.

### Mandatory filters

The app excludes, for example, the following types of sections:

* `highway=motorway` – motorways,
* `bicycle=no` – cycling prohibited,
* `access=private` without an exception,
* `construction` – construction sites or roads under construction.

---

## Chapter 9: Variable Route Settings

### Why are there multiple profiles?

Each bike type and route style uses its own profiling logic because different riders have different requirements:

* **Road bikes** require primarily high-quality and smooth surfaces.
* **Gravel bikes** can handle a mix of asphalt and light off-road sections.
* **MTB bikes** are suitable for off-road and technical sections.

### How does profiling work?

Profiling is based on a combination of several factors:

1. **Bike type** – determines which surfaces and roads are physically suitable.
2. **Route style** – determines the trade-off between speed, safety, and distance.
3. **User preferences** – for example excluding stairs, restrictions, or risky sections.

### Profile combination examples

#### Road + Safer

* Prefers cycle paths and residential areas.
* Avoids main roads when a suitable alternative is available.
* The route may be longer but safer.

#### Gravel + Faster

* Allows light off-road sections.
* Gives higher priority to speed.
* May choose a faster option over gravel or unpaved roads.

#### MTB + Safer

* Allows off-road sections.
* Avoids dangerous or unsuitable paths.
* Prefers safer passage through terrain.

---

## Chapter 10: Typical Use Cases

### Use Case 1: Daily commute to work

1. Launch BRP.
2. Select **Commute** and the **Faster** style.
3. Select the start point, for example home.
4. Select the destination, for example work.
5. Start navigation.

### Use Case 2: Weekend trip

1. Launch BRP.
2. Select **Gravel** or **Touring**.
3. Select **Safer** or **Touring / Balanced**.
4. Select the destination and review the suggested route.
5. Start navigation.

### Use Case 3: MTB ride

1. Launch BRP.
2. Select **MTB**.
3. Select **Safer** or **Touring / Balanced**.
4. Select an off-road destination.
5. Start navigation.

### Use Case 4: Loop ride

1. Launch BRP.
2. Select **Gravel** or **MTB**.
3. Tap **Loop**.
4. Set the distance, for example **30–50 km**.
5. Generate the loop and adjust its points if needed.
6. Start navigation.

---

## Chapter 11: General Tips

### Tip 1: Check map data coverage

Before planning a longer route, check whether you have downloaded the required segments:

1. Tap **Offline data**.
2. Check whether the segments for the selected area are available.
3. If they are missing, download them in BRouter.

### Tip 2: Use GPS for quick start selection

1. Tap the GPS icon.
2. Wait until the icon turns green.
3. Confirm the use of your current location.

### Tip 3: Check warnings before riding

Before starting the ride, it is recommended to:

1. Check orange warnings on the map.
2. Read the explanation of problematic sections.
3. Consider whether the route matches your abilities and bike type.

### Tip 4: Pause is safe

If you need a break:

1. Tap **Pause**.
2. The app will continue tracking your location.
3. After resuming, navigation will continue from the current or last known location.

### Tip 5: Use Bike Radar Overlay

If you use Bike Radar Overlay:

1. Install **Bike Radar Overlay**.
2. Start navigation in BRP.
3. You can view navigation instructions even when the screen is locked.
4. If Bike Radar Overlay also shows radar alerts, those alerts take priority over navigation instructions.

---

## Frequently Asked Questions

### Why does route calculation take so long?

Offline route calculation may take a few seconds. The calculation time depends on:

* route length,
* complexity of the area,
* device performance,
* GPS signal availability,
* availability of downloaded map data.

### Why does the app not suggest off-road routes?

This depends on the selected profile:

* **Road** usually avoids off-road sections.
* **Gravel** allows light off-road sections.
* **MTB** is intended for off-road sections as well.

Check your bike type and route style settings.

### Why is navigation not shown in Bike Radar Overlay?

Check the following:

1. Bike Radar Overlay is installed.
2. You have actually started navigation in BRP, not only route planning.
3. Bike Radar Overlay has the required permissions, such as notification permission.

### Why is the route recalculated after pausing?

The app may automatically recalculate the route if you move away from the original route.

This typically happens when:

* you move more than approximately **18 meters** away from the route,
* the app decides that a new route from the current location is needed.

### Why is the route not displayed on the map?

Check the following:

1. the GPS signal is stable,
2. map data has loaded,
3. an internet connection is available during the first map load,
4. the required BRouter segments for the area have been downloaded.

---

## License Information

The app uses:

* **BRouter** – GPL-3.0, offline routing.
* **osmdroid** – Apache-2.0, map display.
* **OpenStreetMap** – ODbL, map data.

---

## Acknowledgements

The app was created to support the cycling community and provide a route planning tool focused on safety, comfort, and flexibility.

Thank you for your support and for using **Bike Route Planner**.
