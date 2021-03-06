#### Fragments

Fragments are a powerful UI concept in Android. They represent a self-contained UI portion of an Activity's layout and logic.

Here's some stuff that you should read about them:
- [Fragments Design Philosophy, Fragments Lifecycle](http://developer.android.com/guide/components/fragments.html)
- [Dynamic UI with Fragments (see the three links below)](http://developer.android.com/training/basics/fragments/index.html)
- [Check out the sample (Eclipse project)](http://developer.android.com/shareables/training/FragmentBasics.zip) 
 

Try to answer the following questions:
- Why were fragments introduced in Android 3.0/4.0? 
- When should you use fragments? 
- What is a `FragmentManager`? What is a `FragmentTransaction`?
- How would a `Fragment` communicate with it's host `Activity`?
- Should Fragment A **know** about Fragment B? If not, how would they communicate?

#### AsyncTasks
Easily manage both background and UI calculations:
- [AsyncTask reference](http://developer.android.com/reference/android/os/AsyncTask.html)
- [AsyncTask tutorial](http://www.vogella.com/tutorials/AndroidBackgroundProcessing/article.html)
- [AsyncTask retain configuration change](http://www.androiddesignpatterns.com/2013/04/retaining-objects-across-config-changes.html)

Try to answer the following questions:
- How would you implement AsyncTask yourself?
- What would you use AsyncTask for?
- How can an AsyncTask cause a leak?
