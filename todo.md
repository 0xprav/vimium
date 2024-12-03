Closing Tabs and Adding to Recently Closed List
Close the tab: Use the chrome.tabs.remove() method to close the desired tab.
Store tab information: Before closing the tab, capture its URL and other relevant information.
Add to recently closed list: Unfortunately, there is no direct way to add a tab to Chrome's built-in recently closed list. However, you can use the chrome.sessions API to store and manage your own list of recently closed tabs.
