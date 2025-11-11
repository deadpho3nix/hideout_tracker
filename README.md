# Tarkov Hideout Tracker

Tarkov Hideout Tracker is a WPF-based application designed to help players of **Escape from Tarkov** track their progress in collecting items, completing quests, and upgrading their hideout. The application provides a clean and modern interface to manage your progress efficiently.

---

## Features

- **Item Tracking**: Keep track of the items you need for hideout upgrades and quests.
- **Quest Management**: View and manage quests, including Kappa-required quests.
- **Trader Filtering**: Filter quests by specific traders.
- **Progress Persistence**: Automatically saves your progress and settings.
- **Update Checker**: Check for new versions of the application directly from the app.
- **User Data Management**: Easily reset your progress with the "Wipe User Data" option.

---

## How to Use

1. **Hideout Tab**:
   - The left panel displays a list of items required for hideout upgrades.
   - The right panel shows the available upgrades.
   - Use the search boxes to filter items or upgrades.
   - Click on an item to increase its progress or right-click to decrease it.
   - If you don’t want to track a specific upgrade, you can check the Deactivate box.
   - If you’ve already completed Hideout upgrades, you can also check them off — they’ll be accurately removed from the list of required items.

2. **Quests Tab**:
   - View all available quests and their required items.
   - Use the trader icons at the top to filter quests by trader.
   - Check the "include quest items" box to include quest-related items in your item list.
   - Check the "only include Kappa relevant" box to filter for Kappa-required quests.
   - Quest items are displayed with their required quantities. If the list of items is too long, it will wrap to the next row for better visibility.

3. **Update Tab**:
   - Check your current version and see if a new version is available.
   - If an update is available, click the "Update" button to download and install it.

4. **Options Tab**:
   - Use the "Wipe User Data" button to reset all progress and settings. A confirmation dialog will appear before the data is wiped.

---

## Current Limitations

- **Quest Data**: Currently, the application includes primarily Kappa-required quests. Additional quests will be added in future updates.
- **Tarkov 1.0 Wipe**: Changes introduced in the 1.0 Tarkov wipe will be incorporated into the application in future patches.

---

## Future Plans

- Add more quests beyond Kappa-required ones.
- Implement changes from the Tarkov 1.0 wipe.
- Enhance the user interface with additional customization options.
- Add support for more detailed progress tracking.

---

## System Requirements

- **Operating System**: Windows 10 or later
- **.NET Version**: .NET 8
- **Dependencies**: The application uses `Newtonsoft.Json` for data handling.

---


## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for new features, please open an issue or submit a pull request.

---

## Disclaimer

This application is not affiliated with or endorsed by Battlestate Games. All trademarks and copyrights are the property of their respective owners.
