### Nitro Gadgets Search Project

Hosted Link: [Nitro Gadgets Search Project](https://sudhanshusudan33.github.io/Phone_hunting/)

This project allows users to search for phones and view their details. It includes a search bar, a loading spinner, and a grid layout for displaying phone cards.

### How It Works

1. **Search Functionality**: 
   - Users can enter a search term (e.g., "Samsung") in the search bar.
   - The searchHandler function fetches phone data from an API based on the search term.
   - Phone cards are displayed based on the search results.

2. **Loading Spinner**:
   - The loading function shows or hides a loading spinner while fetching phone data.

3. **Displaying Phones**:
   - The displayPhones function creates phone cards for each phone in the search results.
   - Phone cards include the phone's image, name, and a "Show Details" button.

4. **Show All Button**:
   - The "Show All" button appears when there are more than 12 search results.
   - Clicking the button displays all search results without pagination.

5. **Modal for Phone Details**:
   - Clicking the "Show Details" button on a phone card opens a modal with detailed information about the phone.
   - The showPhoneDetails function populates the modal with the phone's image, name, brand, specifications, and release date.

6. **API Calls**:
   - The project uses fetch to make API calls to retrieve phone data.
   - API endpoints are used to search for phones and retrieve detailed information about a specific phone.

### JavaScript Functionality Used

- **Fetch API**: Used to fetch phone data from an external API.
- **Dynamic DOM Manipulation**: Used to create and display phone cards based on search results.
- **Event Handling**: Used to handle user interactions such as clicking buttons and displaying modals.
- **Asynchronous JavaScript**: Used async/await to handle asynchronous API calls.
- **Conditional Rendering**: Used to show/hide elements based on certain conditions (e.g., number of search results).
- **Modal Interaction**: Used to display detailed information about a phone in a modal.