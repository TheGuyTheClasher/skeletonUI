# skeletonUI

A skeleton screen is an animated placeholder that simulates the layout of a website while data is being loaded.

They let the user know that some content is loading and, more importantly, provide an indication of what is loading, whether it's an image, text, card, and so on.

This gives the user the impression that the website is faster because they already know what type of content is loading before it appears. This is referred to as perceived performance.

# how to?

It is important to note that skeleton UI only loads if the network speed is slow or in a real world scenario the incoming data is way to much and needs time.

## Lets reproduce the slow network speed scenario.

1. Open DevTools (Ctrl+Shift+i).
2. Navigate to the "Network" tab.
3. Select the type of connection you want by clicking on 'No throttling' dropdown, select slow 3G.
4. Reload the page to see assets downloading at the specified connection speed.
5. Remember not to close the DevTools.
