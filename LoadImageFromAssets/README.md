LoadImageFromAssets
=======

This class allow you load an Image from assets easily. 
Example of the use:

	 ImageView = findViewById(R.id.myImageView);
	 LoadImageFromAssets loadImage= new LoadImageFromAssets(context);
     loadImage.resizeIfLandscape(640, 480); //Optional
     loadImage.loadImage(iv, "images/image1.jpg");
