# UI-UX-Experiment3

## Aim:

To design and develop a responsive, user-friendly mobile e-commerce homepage interface for Flipkart that optimizes product discovery, highlights promotional campaigns, and integrates interactive shopping features like video consultations.

## Algorithm:

1: Initialize LayoutCreate a scrollable parent container (ScrollView or RecyclerView).Set up a fixed top navigation bar and a sticky bottom navigation menu.

2: Render Top Header & NavigationInject the brand logo and dynamic icons (Notifications, Wishlist, Cart with dynamic badge count).Render a global Search Bar component with embedded vector icons for camera-based visual search.Display a horizontal scrolling list (LazyRow or UICollectionView) containing category shortcuts with circular image assets and labels.

3: Load Dynamic Promotional BannersFetch active campaign data (e.g., "Big Saving Days") from the backend API.Implement an automated carousel slider component with indicator dots.Bind click listeners to banners to route users to targeted product listing pages (PLP).

4: Integrate Video Call Feature ComponentCheck system clock against active service hours (10:00 AM – 10:00 PM).If within hours, render the "Shop with an Expert" feature block with an active "Connect Now" button.Bind the button to initialize the WebRTC or third-party video streaming SDK pipeline.

5: Populate Personalization FeedFetch and parse "Best Deals for You" grid data based on user history.Render product cards containing image thumbnails, titles, pricing, and discount percentages.

6: App State & Bottom Navigation ControlListen for user interactions on the bottom tab bar.Switch view fragments natively when tabs change (Home, Categories, Explore, Notifications, Account).

## Output:

<img width="778" height="1600" alt="image" src="https://github.com/user-attachments/assets/2e9e9bb9-1d3f-4fa4-b62f-37f4281f7946" />


## Result:

The system successfully compiles and renders the e-commerce mobile application interface. Users can seamlessly browse categories, view dynamic sale carousels, verify trust badges, and initiate real-time video shopping assistance with a single tap. The layout scales cleanly across modern high-aspect-ratio smartphone displays.
