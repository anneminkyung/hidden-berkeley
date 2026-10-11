# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This guide is for prospective students, UC Berkeley students, staff, and families who are new to Berkeley or want to explore the campus. It introduces study spaces, campus services, and various places to visit on and around campus. Each resource includes location details, access notes, and an official website link to help visitors plan their visit.
I added the [Inclusive Excellence Hub](https://grad.berkeley.edu/students/finding-community/inclusive-excellence-hub/), which is a place where graduate students can study, build meaningful connections, and find their community.
I also updated the D-Lab resource to provide more information about its workshops and research consultations. I used the official [D-Lab Workshops page](https://dlab.berkeley.edu/workshops/) to find details about the available workshops.


## Website checks

I checked [my website](https://anneminkyung.github.io/hidden-berkeley/) to make sure that my updated heading and introduction appeared correctly. I also made sure that all nine resources were listed, including the newly added Inclusive Excellence Hub, and that the updated D-Lab access note and Inclusive Excellence Hub details matched the CSV file. Lastly, I checked that both official source links opened the intended pages.