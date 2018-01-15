# gesto [![](https://jitpack.io/v/aboutgaurav/gesto.svg)](https://jitpack.io/#aboutgaurav/gesto) [![API](https://img.shields.io/badge/API-14%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=14)
Close


A simple gesture detection library for android.

## USES

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

    allprojects{
      repositories{
   		...
		maven{ url 'https://jitpack.io'}
      }
    }

Step 2. Add the dependency

    dependencies{
    	compile 'com.github.aboutgaurav:gesto:0.1.0'
   	}

Step 3. Obtain your view refernce and set listener

	//Obtain your view reference
        View view = findViewById(R.id.view);
	
	//Set listener
        view.setOnTouchListener(new OnGestureListener(this) {
            @Override
            public void onSwipeRight() {
                super.onSwipeRight();
                //todo
            }

            @Override
            public void onSwipeLeft() {
                super.onSwipeLeft();
                //todo
            }

            @Override
            public void onSwipeTop() {
                super.onSwipeTop();
                //todo
            }

            @Override
            public void onSwipeBottom() {
                super.onSwipeBottom();
                //todo
            }

            @Override
            public void onClick() {
                super.onClick();
                //todo
            }

            @Override
            public void onDoubleClick() {
                super.onDoubleClick();
                //todo
            }

            @Override
            public void onLongClick() {
                super.onLongClick();
                //todo
            }}

        );
	
  To remove gesture listener
  
  	view.setOnTouchListener(null);
