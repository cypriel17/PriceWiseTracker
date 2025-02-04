# Price Tracker App

This is a React Native application that allows users to track product prices on Amazon. The app integrates with Supabase for backend services and uses Bright Data for web scraping. Users can search for products, track price changes, and receive notifications when prices drop.

## Features

- **User Authentication**: Sign up, sign in, and sign out functionality.
- **Product Search**: Search for products on Amazon and save search queries.
- **Price Tracking**: Track price changes for saved searches.
- **Price Drop Notifications**: Receive notifications when prices drop for tracked products.
- **Product Details**: View detailed information about products, including price history.

## Technologies Used

- **React Native**: For building the mobile application.
- **Expo**: For development and deployment.
- **Supabase**: For backend services, including database and authentication.
- **Bright Data**: For web scraping product data from Amazon.
- **Day.js**: For date and time manipulation.
- **Expo Vector Icons**: For icons in the app.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/cypriel17/PriceWiseTracker.git
   cd PriceWiseTracker
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following variables:
   ```env
   EXPO_PUBLIC_SUPABASE_URL=your-supabase-url
   EXPO_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   BRIGHT_DATA_API_KEY=your-bright-data-api-key
   ```

4. **Run the app**:
   ```bash
   npm start
   ```

## Usage

1. **Sign Up/In**: Create a new account or sign in with an existing one.
2. **Search for Products**: Enter a product name or keyword in the search bar.
3. **Track Products**: Save searches and track price changes.
4. **View Product Details**: Click on a product to view its details and price history.
5. **Receive Notifications**: Get notified when prices drop for tracked products.

## Screens

- **Home Screen**: Displays tracked searches and allows new searches.
- **Search Results Screen**: Shows products related to the search query.
- **Product Details Screen**: Displays detailed information about a product, including price history.
- **Login/Signup Screen**: For user authentication.

## Components

- **Button**: A reusable button component.
- **SearchListItem**: Displays a search item in the list.
- **TabBarIcon**: Icon for the tab bar.
- **Container**: A container component for layout.

## Supabase Functions

- **scrape-start**: Initiates a scraping job for a search query.
- **scrape-complete**: Handles the completion of a scraping job and updates the database.
- **check-search-price-drops**: Checks for price drops in tracked searches and notifies users.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Supabase](https://supabase.io) for providing the backend services.
- [Bright Data](https://brightdata.com) for the web scraping capabilities.
- [Expo](https://expo.io) for the development tools and services.

---

This README provides an overview of the Price Tracker App. For more detailed information, please refer to the code and comments within the project.
