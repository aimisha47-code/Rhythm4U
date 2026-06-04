# Rhythm4U
🧘‍♀️ Rhythm4U — A serene, front-end music sanctuary designed to help users unwind, feel the zen, and align their mood with their favorite artists.The application provides custom frontend views for profile management, data visualization dashboards, custom music reviews, user playlist collections, mood-based music generation, dedicated favorite tracklists, and live media playback.
**Features Included**
  1. User Authentication Flows: Secure frontend navigation handling login (index.html), account registration (signup.html), and session exit capabilities via a functional Logout button.
  2. Interactive Data Visualization Dashboard: Integrated dynamic analytics using Chart.js to track user listening habits on homepage.html. This includes a weekly hour progress gauge, a monthly top tracks bar chart, and a genre breakdown doughnut chart.
  3. "Vibe Check" Mood-Based Recommendation Engine: An interactive interface featuring selectable mood category blocks (Calm, Dreamy, Energetic, and Melancholy). Clicking a category dynamically triggers a modal populated with track listings specifically curated to fit that vibe.
  4. Curated Favorites Hub: A dedicated user space (favourite.html) showcasing the user's top bookmarked tracks complete with album art, track runtimes, and immediate media-player engagement controls.
  5. Music Review Board: A dynamic review platform allowing users to submit album or song titles, attach cover image URLs, select a star rating, and write personal thoughts, along with the ability to clear/delete existing posts.
  6. Curated Playlist Collection Manager: An interactive library panel where users can expand their custom audio collections by inputting a playlist title and an associated YouTube streaming link.
  7. Persistent Audio Media Player: A floating audio playback bar equipped with album artwork, live tracking metrics, play/pause functions, and an interactive slider for volume adjustments.
  8. Navigation Architecture: Clean top navigation headers managing pathways to Artists, Reviews, Playlists, and Favourites (heart icon), balanced with footer utility sub-menus for Home, Profile, and Settings.
     
**Instructions to Test Login and Features**
To explore the authenticated features of the website, please use the following credentials:
Test Username / Email: aimi@gmail.com
Test Password: 1234

Step 1: Initial Authentication
1. Navigate to the live website link (defaults to your landing login layout).
2. Enter the test credentials above.
3. Click login to be redirected to the main profile dashboard (homepage.html).

Step 2: Testing the "Vibe Check" Mood Selector
On the main dashboard, scroll down to the "Vibe Check" section.
1. Click on any of the interactive mood panels (Calm, Dreamy, Energetic, or Melancholy).
2. Verify that a modal container labeled "Recommended Tracks for your [Selected] Mood" dynamically pops up over the page.
3. Click the pink Play action button next to any track inside the list to test user feedback on the persistent bottom audio player.

Step 3: Testing the Favorites Hub
Navigate to the top right corner of the header layout and click the Heart Icon button to open the Your Favorites screen (favourite.html).
1. Review the list of curated favorite songs.
2. Click the Play button (▶) icon on the right side of any song track module.
3. Confirm that the music target updates in real time to populate the floating playback control bar below.

Step 4: Testing the Music Review Feature
Click REVIEW in the top navigation bar to open the review module.
1. Under "Write a Review", fill out the Album or Song Title, insert an image address URL, choose a star rating from the dropdown menu, and type a comment into the text area.
2. Click Post Review to see your item dynamically populate below the form.
3. Test the removal functionality by clicking Delete Review on a posted item.

Step 5: Testing the Playlist Manager
Click PLAYLIST in the top navigation bar to access the curation dashboard.

1. Locate the input fields below the "Curated Playlists" header.
2. Type a name into the Playlist Name... field and paste a valid link into the YouTube Link... box.
3. Click Add to Collection to watch your custom playlist card render in the library block.
4. Click Open YouTube on any card to test external media mapping, or click the "X" button in the corner of a card to remove it.

**Frameworks / Libraries Used**
The project was built utilizing the following technologies and frameworks:
  1. Core Frontend Architecture: HTML5, CSS3 (Custom responsive style modules arranged in /CSS/), and JavaScript (ES6+).
  2. Data Visualization Engine: Chart.js (loaded via the jsdelivr.net Content Delivery Network) to render custom-themed,     interactive analytics graphs.
  3. Asset Integration: FontAwesome / Custom media assets for interface icons and player design components.
  4. Deployment hosting: Deployed seamlessly using GitHub Pages for public preview.

