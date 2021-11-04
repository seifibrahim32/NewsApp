# NewsApp.
News Application made with Java language and with some networking methods
to get from the server the information of the news with the author name and the 
time and its date.

# How it works.
The user opens the app with the internet connection to get news list , so 
the list appears so give the user the ease of clicking on the list for 
extraction  of bunch of information and many more will be discussed in Features section.

# Used Technologies in the Application:
- RetroFit.
- Verbose Debugging.
- ArrayList.
- SwipeRefreshLayout.
- ApiKey from NewsApi.Org to fetch the information.
- RecyclerView.
- SearchView.
- Glide.
- ClickListener.
- CardView.
- PrettyTime.
- CoordinatorLayout.

# Features
- [x] Easy for the user to user.
- [x] Easy to make searches.
- [x] If there is no internet connection or cellular data, app won't work.
- [x] Catchy User Interface <3.

# Important details of the app.
- AndroidManifest.xml : File for internet permission and the app icon visibility.   
- Two activities are in the app:
- MainActivity.java :
When you open the app ,this MainAcitivty.java works and also recalls the content from the res/layout/activity_main.xml and incluede the error.xml exception
with the ids of each one after recalling , RetroFit creates new instance through ApiClient.java and recalls on ApiInterface.java to extract the data as well as
implemented initListener() declared for filling the onItemClickListener object in Adapter.java.
- [x] OnResponse : trying the information if it recalled the API and RecyclerView implementation occurs.
- [x] On Failure : Appearing the error.xml which included by activity_main.xml.
-QueryListener is made also if user needs to find an information by himself.
- Adapter.java: A java file for binding RecyclerView which set in MainActivity.java
- "models" folder : Full of pojo files for ability to retrieve data from JSON file of NewsApi.org.
- NewsActivity.java : OnClickListener switch to the intent of MainActivity.java from the adapter.
It shows the WebView and the information of the article as there is a reliability to share the news or open it from a browser.

# Used websites for the app:
- www.jsonschema2pojo.org
- RetroFit Documentation
- Android Documentation
- NEWSAPI.org


