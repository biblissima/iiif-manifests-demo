# iiif-manifests-demo

This repository contains IIIF manifests created as part of Biblissima's demos to fulfill specific use cases in the field of manuscripts studies. These demos make use of the [Mirador viewer](http://projectmirador.org) to display the digital objects.

Online demos on Biblissima website: [http://demos.biblissima-condorcet.fr](http://demos.biblissima-condorcet.fr)

Here is a short description of each demo and the specific character of the manifest:

###**Proto-BBMN 1713**

Virtual reconstruction of the primitive state of the _Bibliotheca bibliothecarum manuscriptorum nova_ (in 1713), a huge "catalogue of catalogues" of manuscripts from more than 200 libraries in Europe, by Bernard of Montfaucon. The work of identification and reconstruction has been made by Jérémy Delmulle (postdoctoral researcher, KU Leuven – IRHT – BnF), the IIIF manifest by Régis Robineau.

IIIF Manifest (see `bbmn-1713` folder):
- empty canvases (lacunae)
- canvas-level metadata

Manifest URLs: 
-  Tome I: [http://iiif.biblissima.fr/bbmn-1713-t1/manifest.json](http://iiif.biblissima.fr/bbmn-1713-t1/manifest.json)
-  Tome II: [http://iiif.biblissima.fr/bbmn-1713-t2/manifest.json](http://iiif.biblissima.fr/bbmn-1713-t2/manifest.json)
- Idex: [http://iiif.biblissima.fr/bbmn-1713-index/manifest.json](http://iiif.biblissima.fr/bbmn-1713-index/manifest.json)

[Go to demo page](http://demos.biblissima-condorcet.fr/bbmn-1713/)

###**Grandes Chroniques de France - Châteauroux BM ms. 5**

Virtual reconstruction of the original state of a French medieval manuscript (Châteauroux BM ms. 5: _Grandes Chroniques de France_, 15th century). The manuscript's 14 illuminations were cut out at some point in the past and eventually ended up at the BnF in the 19th century. The full manuscript and the individual cuttings have been digitized and made available online, in the BVMM and in Gallica respectively. The manifest attempts to virtually reconstruct the original manuscript by repositioning the miniatures on top of the corresponding gaps in the mutilated pages. This use case has been suggested by François Bougard and the manifest has been created by Régis Robineau.

IIIF Manifest (see `chateauroux-bm-ms-5` folder):
- canvases with two image annotations, the second one targeting a specific region of the canvas (illumination cuttings)

Manifest URL: [http://demos.biblissima-condorcet.fr/iiif/metadata/BVMM/chateauroux/manifest.json](http://demos.biblissima-condorcet.fr/iiif/metadata/BVMM/chateauroux/manifest.json)

[Got to demo page](http://demos.biblissima-condorcet.fr/chateauroux/)
[Watch a video demo](http://www.youtube.com/watch?v=xYmbGmJjrEA&t=11m17s)


###**Codex Florus "dispersus"**

Virtual reconstruction of a dispersed manuscript of letters and sermons by Augustine (Paris, Geneva, St. Petersburg), with digital images coming from e-codices and Gallica. The reconstruction has been made by Pierre Chambert-Protat and the IIIF manifest by Elena Koroleva.

IIIF Manifest (see `florus-dispersus` folder):
- empty canvases (lacunae)
- use of Ranges to represent the codicological structure of the original manuscript

Manifest URL: [http://demos.biblissima-condorcet.fr/iiif/metadata/florus-dispersus/manifest.json](http://demos.biblissima-condorcet.fr/iiif/metadata/florus-dispersus/manifest.json)

[Got to demo page](http://demos.biblissima-condorcet.fr/florus/#florus-dispersus)

###**Florus manuscripts from Lyon**

IIIF Manifests for 3 manuscripts held at the Public Library of Lyon (France), created for a demo which intend to gather in a Mirador viewer a set of manuscripts related to Florus of Lyon (autographs manuscripts or annotated by his hand). The manifests use the Image API endpoint of the Lyon Public Library, they have been made by Pierre Chambert-Protat and Régis Robineau.

IIIF Manifests (see `ms-florus-bm-lyon` folder).
Manifests URLs:
- Lyon, BM, Ms. 484: [http://iiif.biblissima.fr/manifests/B693836101_MS0484/manifest.json](http://iiif.biblissima.fr/manifests/B693836101_MS0484/manifest.json)
- Lyon, BM, Ms. 604: [http://iiif.biblissima.fr/manifests/B693836101_MS0604/manifest.json](http://iiif.biblissima.fr/manifests/B693836101_MS0604/manifest.json)
- Lyon, BM, Ms. 788 [http://iiif.biblissima.fr/manifests/B693836101_MS0788/manifest.json](http://iiif.biblissima.fr/manifests/B693836101_MS0788/manifest.json)

[Go to demo page](http://demos.biblissima-condorcet.fr/florus/#manuscrits-florus)

---

For more information about IIIF at Biblissima:
- IIIF repositories at Biblissima: [http://doc.biblissima-condorcet.fr/entrepots-iiif-biblissima](http://doc.biblissima-condorcet.fr/entrepots-iiif-biblissima)
- IIIF images used in the Biblissima portal: [http://biblissima.fr/en/licences](http://biblissima.fr/en/licences)


