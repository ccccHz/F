# Access this dataset

me

Our read-only mount feature is the fastest way to access repositories of any size, streaming files to your machine in seconds. Mount provides a file-system view of repositories for smooth access from any application, whether you're using notebooks, code, or your Finder window. 

If you haven't already, [install and authenticate](https://xethub.com/explore/quickstart), then dive in to see what's in this 4GB Flickr dataset.

## Mount 

Run this command to mount Flickr30k on your machine for fast read-only access. 
```
xet mount xet://XetHub/Flickr30k/main Flickr
```

This command is always available via the purple Access button right above this README.

## Explore

Our Flickr30k dataset includes a 13.9MB `results.csv` file that lists 5 annotations per image, as well as around 32K images organized by the first two numbers of each file name. Phew. 

Dust off your favorite file or photo browser to navigate to **13/131090759.jpg**, which shows how we all feel when we have to lug our big files around to do our jobs. And while you're at it, click around some more to see the randomness of public internet images.

When you're done exploring the files, unmount with this command or by ejecting the drive through your file explorer:
```
umount Flickr/
```

## Next steps

🐛 This dataset is not perfect. Check out the [pull requests](https://xethub.com/XetHub/Flickr30k/pulls) to see what collaborative dataset review looks like.

🎓 Read more about [advanced CLI, Python, and AWS CLI access patterns](https://xethub.com/assets/docs/category/advanced).

🛠️ Want to get more hands on? Follow our docs to [make your first changes](https://xethub.com/assets/docs/getting-started/hello#duplicate-or-clone-to-develop) to a XetHub repository!



# About this dataset

The Flickr30k dataset has become a standard benchmark for sentence-based image description. This paper presents Flickr30k Entities, which augments the 158k captions from Flickr30k with 244k coreference chains, linking mentions of the same entities across different captions for the same image, and associating them with 276k manually annotated bounding boxes. Such annotations are essential for continued progress in automatic image description and grounded language understanding. They enable us to define a new benchmark for localization of textual entity mentions in an image. We present a strong baseline for this task that combines an image-text embedding, detectors for common objects, a color classifier, and a bias towards selecting larger objects. While our baseline rivals in accuracy more complex state-of-the-art models, we show that its gains cannot be easily parlayed into improvements on such tasks as image-sentence retrieval, thus underlining the limitations of current methods and the need for further research.

License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
