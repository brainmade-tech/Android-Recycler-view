# HiddenFounders_YcDev
This code was made by YcDev

The project depends on some libraries (Dependencies), so before trying to write any piece of code, make sure that you added
the following dependencies in your grade file "build.gradle" :

### Retrofit (Http client) + Gson
compile 'com.squareup.retrofit:retrofit:2.0.0-beta2'
compile 'com.google.code.gson:gson:1.7.2'
compile 'com.squareup.retrofit:converter-gson:2.0.0-beta2'
compile 'com.squareup.okhttp:okhttp:2.4.0'

### RecyclerView
compile 'com.android.support:recyclerview-v7:26.1.0'

### Picasso
compile 'com.squareup.picasso:picasso:2.5.2'

# Choices

* Retrofit : it will help us to consume the WebService that provides data formatted in JSON
* GSON : it will help use to convert from/to JSON, we can say that it acts like an "ORM"
* RecyclerView : here I used RecyclerView instead of ListView because the first one has a good performance and enhancements than the second one
* Picasso : it will help us to use/display a remote image into a ImageView without writing a lot lines of code, we'll write only
one where we provide the Image URL.

# 3 Layers architecture
In this code I had tried to make a 3 layers architecture to achieve separation of concerns, modularity, legibility and maintainability. Here are the used packages :
* models : contains POJOs for carrying data
* dao : to manage code that interacts directly with datasource
* business : contains the application logic
* my application : contains the presentation



# Finally

I hope that I can join the HiddenFounders Team and here is my email address : yassinechaoui.dev@gmail.com

Cheers !!
