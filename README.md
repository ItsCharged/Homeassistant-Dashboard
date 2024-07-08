***My Homeassistant (Tablet) Dashboard***

This was created by using a lot of custom ressources. I recommend you checking them out. (look below)

There are 2 release options: Redacted and not redacted.
The diffrence between them, is that one uses (not redacted) shows all my entitys and my config (some entitys / configs have been redacted anyways, for privacy reasons.)
The redacted one only shows Template cards which you can change and fit to your liking. It shows basic ways to animate, using (adaptive) icons and colors.
I mainly use the normal cards for turning things on/off and for opening popups.

IMPORTANT: Even if it the dashboard is not redacted Weather service (shows my position excactly) and device ids from the browser mod popups and more things that could have been sensitive i have removed.

***Tutorial on how to set up dashboard & Theme:***
1. Get the Latest code from [Data](https://github.com/ItsCharged/Homeassistant-Dashboard/tree/main/Data)
2. Create new homeassistant Dashboard by [⚙️]Settings -> [◻️]Dashboards -> [➕]Create Dashboard -> [✐]New Dashboard from Ground up
3. Go to dashboard then click ✐ -> ⫶ -> {}Raw Configuration Editor
4. Paste in Dashboard Code

 For Theme:

 1. Open File manager
 2. Locate folder 'themes' (if not there create it)
 3. Create new folder
 4. Name it like your theme
 5. Create file in that folder
 6. Name it [Name it like your theme].yaml
 7. Add newest Theme Code
 8. Edit the 2nd row of the yaml and change the text before the : to your themes name (very important: Dont forget that spaces aren't allowed! Use minus instead.)

***Requirements for redacted & unredacted versions***

___Its Strongly recommended to use hacs, so please do so by installing  [Hacs](https://hacs.xyz/docs/setup/download)___

***Redacted:***

Card Mod

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=thomasloven&repository=lovelace-card-mod&category=plugin)

Button Card

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=custom-cards&repository=button-card&category=plugin)

Layout Card

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=thomasloven&repository=lovelace-layout-card&category=plugin)

Simple Weather Card

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=kalkih&repository=simple-weather-card&category=plugin)

Vertical Stack in Card

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=ofekashery&repository=vertical-stack-in-card&category=plugin)


***Unredacted:***

Better Thermostat UI (Using as Pool Card, looks cooler and more functions):

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=KartoffelToby&repository=better-thermostat-ui-card&category=plugin)

Hass Hue Icons (Using it for a lot of buttons)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=arallsopp&repository=hass-hue-icons&category=plugin)

Scheduler Card (Using it in one of my popups: Its a dream for automating your Heating, Clock, Daily Tasks and more) NEEDS FRONTEND + BACKEND

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=nielsfaber&repository=scheduler-card&category=plugin)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=nielsfaber&repository=scheduler-component&category=integration)

Mini-Graph Card (Using it for my Humidity and Temperature Poups)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=kalkih&repository=mini-graph-card&category=plugin)

Button Card (Core component, needed for most of the dashboard)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=custom-cards&repository=button-card&category=plugin)

Layout Card (Required for my Dashboards Layout)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=thomasloven&repository=lovelace-layout-card&category=plugin)

For Wallpanel there is a nice integration named wallpanel but personally i like fully kiosk more. You pay one time, but i think its worth it. Fully has got a lot of features like hass communication, motion detection, very good error of website detection (shows when offline reconnects when online tries to reconnect to wifi network) and a ton of more features i cant put in this description so go check out both of them and see whats better for you :)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=j-a-n&repository=lovelace-wallpanel&category=plugin)

https://www.fully-kiosk.com/en/

 Mushroom (Standard Mushroom is required for the custom areas i set using the chips)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=piitaya&repository=lovelace-mushroom&category=plugin)

Simple weather card (For weather in the sidebar and yes there are 2-3 weather cards in this dashboard. Trust me all of them make sense!)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=kalkih&repository=simple-weather-card&category=plugin)

Weather Radar Card (2nd one: Shows rain on a nice card in my weather popup)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=Makin-Things&repository=weather-radar-card&category=plugin)

Kiosk Mode (Yes this is required in homeassistant to disable the sidebar and header so it  doesent look ugly. In a web browser you can disable the kiosk mode by adding ?disable_km behind the url Example: https[:]//yourhassinstance[.]duckdns[.]org/dashboard-tablet/Standard-Room/***?disable_km***)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=NemesisRE&repository=kiosk-mode&category=plugin)

Battery State Card (used as battery indicator)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=maxwroc&repository=battery-state-card&category=plugin)

Clock Weather Card (used as main weather card in weather popup)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=pkissling&repository=clock-weather-card&category=plugin)

Card Mod (default required by Dashboard)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=thomasloven&repository=lovelace-card-mod&category=plugin)

Restriction Card (i use it to lock my pcs remote functions)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=iantrich&repository=restriction-card&category=plugin)

Vertical Stack in Card (default required by Dashboard)

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=ofekashery&repository=vertical-stack-in-card&category=plugin)
