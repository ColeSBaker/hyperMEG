<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][https://www.linkedin.com/in/cole-baker-724573130/]








<!-- ABOUT THE PROJECT -->
## About The Project

HyperBrain is a inductive learning method that is applicable for any brain imaging modality that focuses on connections between brain regions (ie. MEG, FMRI). Using the natural treelike structure of hyperbolic geometry, it learns node embeddings for each brain region using self-supervised link prediction. These embeddings can be used for downstream classification tasks and analysis.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- USAGE EXAMPLES -->
## Usage
This section will describe the full pipeline of steps, from data ingestion to model training to embedding analysis.
Getting started. Run """conda env create -f environment.yml """
<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- ROADMAP -->
## Roadmap

- [ ] Data Ingestion
    - [ ] Sensor to ROI
    - [ ] Binarize PLV
    - [ ] ROI to RSN

- [x] Model Training
    - [x] Training. The code for this is in train_inductive.py. It can be triggered several ways, most simply by calling main.py.
    - [x] Hyperparameter tuning. The code for this is in hyperparams.py, which runs hyperparameter tuning according to hyperparam_config 
    - [x] Scripts for training experiments for Link Prediction experiments. The code for this is in study_linkprediction. It utilizes the hyperparameter code. This is not quite complete.
            Additionally, it may take up to a day or more to run all combinations. The code is designed to start from where it left off it processes to not complete.


- [x] Embedding Analysis
    - [x] Link Prediction. The code for this is available in link_prediction.ipynb
    - [x] RSN groupings and featurization. The code for this is available in ingest_embedding.ipynb
    - [x] Statistical Analysis. The code for this is available in anova_analysis.ipynb
    - [x] Disease Classificaition. The code for this is available in classification_final.ipynb


- [x] Recreate Plots
    - [x] Statistical Analysis
    - [x] Classification 
    - [ ] Binary Connectivity Matrix
    - [ ] Raw Connectivity Matrix
    - [ ] Diagram of HGCN (Big, pp slide)
    - [ ] Diagram of HGCN (Condensed, pp slide)
    - [ ] Aggregation Visualization
    - [ ] 2D Embedding visualizations

<p align="right">(<a href="#readme-top">back to top</a>)</p>






<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@ColeBakerUSA](https://twitter.com/ColeBakerUSA)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/ColeSBaker/hyperBrain/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/ColeSBaker/hyperBrain/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/ColeSBaker/hyperBrain/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/ColeSBaker/hyperBrain/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
