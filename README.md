# recycam
Did you know the global average of recycling is 19%? Have YOU ever felt unsure about an object's recyclability? Recycam relieves this stressful decision that seems small but actually matters a lot.

We mainly developed Recycam with the use of Python, Swift, and Google Colab. Our project has two main functions–classifying the recyclability of an item and providing the user with general insight about recyclable items.

Here is the python notebook to conduct trash classfication, which was implemented using open-source Computer Vision model on Hugging Face. We specifically used Tag2Text, a vision language pre-training (VLP) framework, to help us identify the names, materials, and colors of the objects in the image. Then we fetched the result from the model and calculated the recyclability score based on the number of tags that have a match in the list of items that are recyclable, which we collected through web scraping. This final score decides whether or not the object goes in the recycling, or the trash. 
