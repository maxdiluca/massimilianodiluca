---
title: How important are detailed hand motions for communication for a virtual character
  through the lens of charades?

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- A. Adkins
- A. Normoyle
- L. Lin
- Y. Sun
- Y. Ye
- M. Di Luca
- S. Joerg

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-07-31T16:44:06.711335Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- 2

# Publication name and optional abbreviated publication name.
publication: '*ACM Transactions on Graphics*'
publication_short: ''

doi: 10.1145/3578575

abstract: 'Detailed hand motions play an important role in face-to-face communication to emphasize points, describe objects, clarify concepts, or replace words altogether. While shared virtual reality (VR) spaces are becoming more popular, these spaces do not, in most cases, capture and display accurate hand motions. In this paper, we investigate the consequences of such errors in hand and finger motions on comprehension, character perception, social presence, and user comfort. We conduct three perceptual experiments where participants guess words and movie titles based on motion captured movements. We introduce errors and alterations to the hand movements and apply techniques to synthesize or correct hand motions. We collect data from more than 1000 Amazon Mechanical Turk participants in two large experiments, and conduct a third experiment in VR. As results might differ depending on the virtual character used, we investigate all effects on two virtual characters of different levels of realism. We furthermore investigate the effects of clip length in our experiments. Amongst other results, we show that the absence of finger motion significantly reduces comprehension and negatively affects people’s perception of a virtual character and their social presence. Adding some hand motions, even random ones, attenuates some of these effects when it comes to the perception of the virtual character or social presence, but it does not necessarily improve comprehension. Slightly inaccurate or erroneous hand motions are sufficient to achieve the same level of comprehension as with accurate hand motions, though they might still affect viewers’ impression of a character. Finally, jittering hand motions should be avoided because it significantly decreases user comfort.'

# Summary. An optional shortened abstract.
summary: 'A set of perceptual experiments testing how changes to virtual-character hand and finger motions affect comprehension, character perception, social presence, and comfort.'

tags:
- virtual character
- gestures
- communication
- animation
- human-computer interaction

# Display this page in a list of Featured pages?
- 'virtual reality'
featured: false

# Links
url_pdf: 'https://research.birmingham.ac.uk/files/183996315/Importance_of_Hand_Motions_for_Communication_Nov22.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://people.computing.clemson.edu/~sjoerg/communication.html'
url_slides: ''
url_source: ''
url_video: 'https://people.computing.clemson.edu/~sjoerg/communication/Adkins23_CommunicationVideo.mp4'

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: 'Virtual-character hand-motion conditions used in the charades experiments.'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
{{< paper_badges "10.1145/3578575" >}}
