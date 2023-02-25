# Firefox-performance-improvements
Let's remove the telemetry, improve the browser

How long do you keep telemetry data?

We keep telemetry data for 13 months.
How do I opt out or delete telemetry data?

You can opt out of sending any Firefox telemetry information at any time. If you opt out of sending telemetry data, we will also treat this as a request to delete any data we previously collected. Data will be deleted within 30 days after you opt out. 

![2019-12-09-21-09-06-aa96a2](https://user-images.githubusercontent.com/108226177/221349644-d519e4e0-fc64-4359-b7ec-cfdb24bb11d3.png)

To opt out of sending any Firefox telemetry information:

    Click the menu button Fx89menuButton and select Settings.
    Select the Privacy & Security panel.
    Scroll to the Firefox Data Collection and Use section.
    Deselect the Allow Firefox to send technical and interaction data to Mozilla checkbox. 

ALL SETTINGS IN ABOUT:CONFIG

Step 1: make fonts like chrome
gfx.font_rendering.cleartype_params.enhanced_contrast 100
gfx.font_rendering.cleartype_params.pixel_structure 0
gfx.font_rendering.cleartype_params.rendering_mode 5

Step 2: disable warning 'you are in full-screen'
full-screen-api.warning.timeout 0
full-screen-api.warning.delay -1

Step 3: disable the fade to black animation when going fullscreen on a video in firefox?
full-screen-api.transition-duration.enter 0 0
full-screen-api.transition-duration.leave 0 0

Step 4: Make scroll faster
mousewheel.min_line_scroll_amount 25 (or what you like)
