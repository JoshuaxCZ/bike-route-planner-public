# User Manual - Bike Route Planner

## Product Overview

**Bike Route Planner** (BRP for short) is an Android application for cyclists that helps you plan routes and provides turn-by-turn navigation instructions during your ride. The app is designed to help you reach your destination safely and efficiently.

### Who is this app for?

The app is designed for all types of cyclists:
- **Road cyclists** - looking for smooth routes on paved surfaces
- **Gravel riders** - wanting a combination of asphalt and light unpaved roads
- **MTB cyclists** - seeking forest trails and technical sections
- **Commuters** - riding daily to work or around the city
- **Tourists** - looking for longer rides with stable pace
- **Explorers** - wanting to discover new sections

### Key Features

- **Offline routing** - no internet connection needed during the ride
- **Custom route planning** - create routes according to your preferences
- **Overlay navigation** - routes from BRP are displayed in VARIA_RADAR app
- **Multiple bike types** - profile selection based on your bike
- **Multiple route styles** - faster, shorter, safer, or balanced
- **Round trip generation** - generate circular routes with configurable distance

---

## Installation and Requirements

### Device Requirements

- **Android 8.0** (API 26) or newer
- **GPS sensor** - required for location services
- **Some free space** for map data

### BRouter Installation

BRP requires the **BRouter** application to be installed. BRouter is an offline routing application created by Filip Němek.

#### How to install BRouter:

1. Open BRP and on first launch you will see a dialog to download BRouter
2. Go to Google Play Store and install the **BRouter** app
3. After installation, open BRouter and download map data for the area where you plan to ride

### VARIA_RADAR Installation (Optional)

If you want to display navigation in an overlay (e.g., on a helmet or head unit), install the **VARIA_RADAR** app.

VARIA_RADAR is an application for detecting vehicles approaching from behind and displaying navigation instructions in lock-screen / riding display mode.

---

## Introduction to Route Planning

### Getting Started

1. Launch the **Bike Route Planner** app
2. On the main screen, tap the **Planner** button
3. Now select the start point and destination

### Selecting the Start Point

- **Use GPS**: Tap the location icon in the top right corner - the app will use your current position
- **Select on map**: Tap and hold on the map where you want the start point to be

### Selecting the Destination

- **Select on map**: Tap and hold on the map where you want the destination to be
- **Cancel destination**: Confirm your selection by tapping the X icon in the top right corner

### Adding Stopovers (Waypoints)

- After selecting the destination, tap the **+** button
- Then tap and hold on the map - this adds a stopover point
- You can add up to 8 stopover points

---

## Bike Types

The app supports 6 bike types, each with different routing profiles:

### 1. Road

**Description**: Road profile focused on paved surfaces, smooth flow and safety.

**Preferences**:
- Asphalt and concrete surfaces
- Cycleways and signed cycle routes
- Residential areas with low speed limits

**Avoids**:
- Off-road paths without paved surface
- Poor quality surfaces
- Technically challenging sections

**Who it's for**: Road cyclists who want a smooth and safe ride.

### 2. Gravel

**Description**: A mix of asphalt, gravel and rideable unpaved roads.

**Preferences**:
- Asphalt and paved surfaces
- Light gravel and rougher terrain
- Quality forest and field roads

**Tolerates**:
- Medium quality unpaved roads
- Tracktype grade 1-3

**Does not allow**:
- Poorly passable surfaces
- Very technical sections

**Who it's for**: Gravel riders who want a combination of road and light off-road.

### 3. MTB (Off-road)

**Description**: Profile for terrain, trails and more technical sections.

**Preferences**:
- Off-road trails and mountain bike routes
- Forest and park paths
- Tracktype grade 1-3

**Tolerates**:
- Unpaved surfaces
- Footpaths, if cycling is allowed
- Quality footpaths

**Avoids**:
- Motor vehicle roads without bicycle permission
- Roads with explicit prohibitions

**Who it's for**: MTB riders who want to ride in off-road terrain.

### 4. Touring

**Description**: Longer rides with stable pace and reliable surfaces.

**Preferences**:
- Reliable surfaces
- Routes with stable speed
- Longer routes with smooth pace

**Tolerates**:
- Medium quality unpaved roads
- Low-speed roads

**Who it's for**: Touring cyclists who want longer rides with comfortable pace.

### 5. Commute

**Description**: Daily transport with emphasis on reliability and time.

**Preferences**:
- Paved surfaces
- Direct routes
- Reliable and familiar roads

**Tolerates**:
- Cycleways
- Residential areas

**Who it's for**: Daily commuters to work or school.

### 6. Explore

**Description**: Discovering new sections even if the route is less predictable.

**Preferences**:
- New and unfamiliar routes
- Combination of surfaces
- Discovering new places

**Tolerates**:
- More risky sections
- Less predictable routes

**Who it's for**: Explorers who want to discover new routes.

---

## Route Styles

Each route style defines how much priority is given to safety, speed or distance:

### 1. Faster

**Description**: Shorter or faster profile. May include busier roads where cycling is legal.

**What it does**:
- Priority on speed and route length
- May accept roads with higher traffic
- If an alternative is faster, it will choose it even through traffic

**Warning**: This style may lead on roads with higher traffic where cycling is legal. Bicycle-forbidden roads are excluded.

**Use when**: You need to reach your destination as quickly as possible and are willing to ride on smaller roads.

### 2. Shortest

**Description**: Preference for the shortest route. May include less comfortable or busier sections where cycling is legal.

**What it does**:
- Priority on minimum route length
- May choose shorter but less comfortable roads
- May lead on roads with higher traffic

**Warning**: This style may lead on less comfortable or busier sections where cycling is legal.

**Use when**: You want the shortest route regardless of comfort.

### 3. Touring (Balanced)

**Description**: Balanced profile for regular rides and longer routes.

**What it does**:
- Compromise between speed, safety and quality
- Accepts medium traffic roads
- Prefers quality surfaces

**Use**: Default choice for most users who want a balanced route.

### 4. Safer

**Description**: Stronger preference for quiet sections, cycleways and lower traffic.

**What it does**:
- Priority on safe routes
- Strongly penalizes main roads without cycling infrastructure
- Prefers cycleways, residential areas and quiet roads

**Use**: When you prefer a quiet ride and are willing to ride longer for greater safety.

---

## Main Interface Overview

### Main Screen

```
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

### Menu (lower left corner)

Tapping the menu icon opens the side menu with additional features:
- **Map planner**: Back to route planning
- **Edit UI**: Size and appearance settings
- **Offline data**: BRouter map data management
- **App settings**: Language, surface, traffic, etc.
- **Support**: Ko-fi support for development
- **Exit**: Close the app

---

## Detailed Feature Guide

### Chapter 1: Selecting Start and Destination

#### GPS Start Selection

1. Tap the **Planner** button
2. Wait for GPS position acquisition (icon in top right)
3. When the icon turns green, position is ready

#### Map Start Selection

1. Tap the **Planner** button
2. Tap and hold on the map where the start should be
3. After a while, a confirmation dialog appears
4. Tap to confirm

#### Map Destination Selection

1. After selecting the start, the **To** button appears
2. Tap and hold on the map where the destination should be
3. After a while, a confirmation dialog appears
4. Tap to confirm

#### Editing Start/Destination

- After selection, you can move the start and destination on the map
- Tap and hold on the point, then move to the new location
- Confirm by tapping

#### Deleting a Point

- Tap the X icon next to the point
- Confirm deletion

---

### Chapter 2: Stopovers (Waypoints)

#### Adding a Stopover

1. After selecting the destination, tap the **+** button (add point)
2. Tap and hold on the map where the stopover should be
3. Confirm your selection

#### Point Order

- Start is always first
- Destination is always last
- Stopovers are prioritized in the order they were selected

#### Changing Order

- Currently cannot change point order
- If you want different order, create a new route

#### Deleting a Stopover

- Tap the **Clear** button
- Select the point you want to delete
- Confirm

---

### Chapter 3: Round Trip Generation

#### How to Generate a Round Trip

1. Tap the **Round trip** button
2. Select the starting position (GPS or map selection)
3. Set target distance:
   - Minimum: 5 km
   - Recommended: 30 km
   - Maximum: 150 km
4. Select number of loop points:
   - Minimum: 3 points
   - Recommended: 6 points
   - Maximum: 9 points
5. Select preferred direction (N, NE, E, SE, S, SW, W, NW)
6. Select ride direction (Clockwise or counter-clockwise)
7. Tap **Generate loop**

#### Editing a Round Trip

- After generation, you can edit points on the map
- Tap **Edit loop** to edit
- Tap **Regenerate** for new calculation

#### Canceling a Round Trip

- Tap **Clear loop**
- The loop will be deleted, but the map remains

---

### Chapter 4: Starting Navigation

#### Start Navigation

1. After completing planning, tap **Go**
2. The app starts processing the route
3. After completion, tap **Go** to start navigation

#### During Navigation

- The app continuously informs you about the status
- Shows instructions for the next turn
- Distance to turn is updated every second

#### Pausing Navigation

- Tap **Pause** to pause
- During pause, instructions are not shown
- Position is still being tracked

#### Continuing After Pause

- Tap **Resume**
- Navigation resumes from the last position

#### Route Recalculation (Reroute)

- If you leave the route, the app automatically recalculates
- Shows new route from current position
- This takes a few seconds

#### Canceling Navigation

- Tap **Cancel**
- Confirm cancellation
- Map remains, navigation ends

---

### Chapter 5: App Settings

#### Language

- **System**: Uses device language
- **English**: English
- **Czech**: Czech

#### Navigation Language

- Same options as app language
- Sets language for instructions and names

#### Default Map Zoom

- Sets default map zoom level
- From 3 (whole country) to 19 (street)
- Recommended: 14

#### Show Cycling Overlay

- Shows signed cycle routes on the map
- Allows seeing signed cycle routes
- Ability to change opacity (25-75%)

#### Show Hiking Overlay

- Shows hiking trails on the map
- Allows seeing signed hiking routes
- Ability to change opacity (25-75%)

#### Navigation Display Settings

- **Minimum zoom**: Distant turns
- **Maximum zoom**: Close turns

#### Custom Route Styling

- **Line width**: From 2 to 18
- **Line color**: Color selection from palette

#### UI Editing

- **Button size**: From 85% to 145%
- **Control size**: Affects size of elements on map
- **Rider icon size**: From 20 dp to 44 dp
- **Navigation banner size**: Text and arrow size settings

---

### Chapter 6: Offline Data (BRouter)

#### How to Download Map Data

1. Tap **Offline data** in menu
2. BRouter information is displayed
3. Tap **Open download manager**
4. In BRouter app, select the area
5. Download segments for the area

#### Checking Availability

- The app automatically checks if segments are downloaded
- If not, a warning is displayed
- Recommended segments are highlighted

#### Recalculating Recommended Segments

- After changing start or destination, segments are recalculated
- Tap **Refresh** to recalculate

---

### Chapter 7: VARIA_RADAR Integration

#### How to Set Up Integration

1. First install VARIA_RADAR app
2. Start VARIA_RADAR and complete setup
3. In BRP, start navigation
4. Navigation data will be sent to VARIA_RADAR

#### What is Transmitted to VARIA_RADAR

- **Distance to turn**: In meters
- **Turn type**: Message like "Right", "Left", etc.
- **Street name**: Name of the street you are on
- **Time to destination**: Estimated Time of Arrival
- **Navigation status**: Active, Completed, GPS Lost

#### Display in VARIA_RADAR

- The app displays navigation on lock-screen (after screen lock)
- If distance is less than 200m, the screen lights up
- Radar alert has higher priority than navigation

---

### Chapter 8: Route Explanation

#### Why Did the App Choose This Route?

The app outputs a route summary:
- **Length**: Total distance
- **Duration**: Estimated time
- **Surface**: Percentage of different surfaces (asphalt, gravel, etc.)
- **Traffic**: Percentage of different traffic levels
- **Risks**: Number of problematic sections (U-turns, sharp turns)

#### Problematic Sections

The app marks problematic sections in orange:
- **Possible U-turn**
- **Sharp reversal**
- **Same-road return**

#### Binding Filters

The app excludes:
- `highway=motorway` (motorways)
- `bicycle=no` (bicycle prohibition)
- `access=private` without exception
- `construction` (construction sites)

---

### Chapter 9: Variable Settings

#### Why Are There Multiple Profiles?

Each bike type and route style has different routing code because:
- **Road bike** needs smooth surface
- **Gravel bike** can handle light terrain
- **MTB** can ride on trails

#### How Does Profiling Work?

Profiling is based on:
1. **Bike type selection** - determines what is physically suitable
2. **Route style selection** - determines how to compromise between safety and speed
3. **User preferences** - exclusion of steps, prohibitions, etc.

#### Profile Examples

**Road + Safer**:
- Chooses cycleways and residential areas
- Avoids main roads
- May be longer but safer

**Gravel + Fast**:
- Allows light terrain
- Priority on speed
- May choose faster route through terrain

**MTB + Safe**:
- Allows off-road
- Prevents dangerous sections
- Prefers safe routes

---

### Chapter 10: Typical Usage Scenarios

#### Scenario 1: Daily Commute to Work

1. Start BRP
2. Choose **Commute** + **Faster**
3. Choose start (home) and destination (work)
4. Start navigation

#### Scenario 2: Weekend Ride

1. Start BRP
2. Choose **Gravel** or **Touring**
3. Choose **Safer** or **Touring**
4. Choose destination and route
5. Start navigation

#### Scenario 3: MTB Ride

1. Start BRP
2. Choose **MTB**
3. Choose **Safer** or **Touring**
4. Choose destination in terrain
5. Start navigation

#### Scenario 4: Round Trip Ride

1. Start BRP
2. Choose **Gravel** or **MTB**
3. Tap **Round trip**
4. Set distance (30-50 km)
5. Generate round trip and edit points
6. Start navigation

---

### Chapter 11: General Tips

#### Tip 1: Check Map Coverage

Before planning a long route, check if segments are downloaded:
1. Tap **Offline data**
2. Check if segments for the area are downloaded
3. If not, download them in BRouter

#### Tip 2: Use GPS Instead of Map Selection

For quick selections:
1. Tap the GPS icon
2. Wait for the green icon
3. Confirm selection

#### Tip 3: Check Warnings

Before starting your ride:
1. Check orange warnings on the map
2. Read explanations of problematic sections
3. Consider if the route matches your abilities

#### Tip 4: Pause is Safe

If you need a pause:
1. Tap **Pause**
2. The app still tracks your position
3. After resuming, continues from the last position

#### Tip 5: Use VARIA_RADAR

If you have VARIA_RADAR:
1. Install VARIA_RADAR app
2. Connect navigation to VARIA_RADAR
3. You can view navigation even with locked screen
4. In case of risk (car from behind), the screen lights up

---

## Frequently Asked Questions (FAQ)

### Q: Why does it take so long to calculate the route?

**A**: Offline routing can take several seconds, depending on:
- Route length
- Route complexity
- Device performance
- GPS signal availability

### Q: Why doesn't the app recommend routes through terrain?

**A**: This depends on the selected profile:
- **Road** excludes terrain
- **Gravel** and **MTB** allow it
- Check your bike type settings

### Q: Why doesn't navigation show in VARIA_RADAR?

**A**: Check:
1. Is VARIA_RADAR installed?
2. Did you start navigation in BRP (not just planning)?
3. Does VARIA_RADAR have notification permissions?

### Q: Why is the route recalculated after pause?

**A**: The app automatically recalculates the route when:
- You leave the route more than 18 meters
- This ensures you are still on the correct route

### Q: Why are routes not showing on the map?

**A**: Check:
1. Is GPS signal stable?
2. Are maps loaded (waiting for GPS)?
3. Do you have internet connection (on first load)?

---

## Support and Feedback

### Where to Find Help?

- **GitHub issues**: https://github.com/JoshuaxCZ/BIKE_ROUTE_PLANNER/issues
- **Ko-fi support**: In the app menu (requires dev mode)

### How to Provide Feedback?

1. Open GitHub issues
2. Describe the problem or suggestion
3. Add information about your device and Android version
4. Attach any screenshots if needed

---

## Versions and Changes

### Version 0.9.13

- Stability and improvements
- Improved routing
- Improved navigation

---

## License Information

The app uses:
- **BRouter** (GPL-3.0) - offline routing
- **osmdroid** (Apache-2.0) - map rendering
- **OpenStreetMap** (ODbL) - map data

---

## Acknowledgments

The app was created with the goal of supporting the cycling community and providing a tool for route planning with an emphasis on safety and comfort.

Thank you for your support and using Bike Route Planner!