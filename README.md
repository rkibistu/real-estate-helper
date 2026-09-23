# real-estate-helper

A simple app that is gonna help me research the real estate prices.
It is not gonna be a full auto crawler. It is gonna be a slower but more targeted app.
The main goal is to automate the process of following specific renting or selling estates (storing details, storing prices, storing changes), to detect when an announcement is closed/deleted and to allow a better visualization of the data with specific filters.
The app should not run continuously, it should run when it is interacted with (ui click, cli cmd, depends what we choose later on dev)

Main flow:
1. i follow different sites like imobiliare.ro or olx.ro; when i see an announcement i am interested in -> i manually copy the URL in a file
2. i press a button: the app gets the details and info from the url, it tries to complete some specific important fields (like year, surface, price, etc.) and it saves it
Now we have details about some different announcements. More url's and data can be added anytime following the same process
4. Later, i can press another button and all stored announcement are checked again to see if there are any changes: different prices maybe, announcement closed/deleted. I want to see all the announcements that got any changes. This changes should not override old data, they should be registered as changes so we can track when every change was made and to see a clear history
5. I am gonna call agents/owners when an announcement get deleted/closed and i am gonna complete some manual info about the announcement: if it was rented/sold or not, the price they agreed on, other fields we think later, and some notes

Later i want to be able to filter by different params i care about: maybe price, maybe location, etc.
