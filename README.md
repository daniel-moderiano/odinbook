# odinbook
A parent repository containing a frontend and backend submodule. This repository was created as the base repo for Heroku deploy, where the backend also serves the frontend. Click either frontend or backend link in the repo to visit those repositories respectively.


<br /> 
<div align="center">
  <br /> 
  
  <p align="center">
    Online therapeutic prescriptions for Australian optometrists
    <br />
    <a href="https://optomrx.net"><strong>Visit the website »</strong></a>
    <br />
    <br />
    <a href="https://github.com/daniel-moderiano/optom-rx/issues">Report Bug</a>
    ·
    <a href="https://github.com/daniel-moderiano/optom-rx/issues">Request Feature</a>
  </p>
</div>




## About the project

[Odinbook](https://odinbook-dm.herokuapp.com/) is a facebook-esque social media website with the ability to create profiles, make posts and comments, and grow you friend network.   

<img src="assets/screenshot.png" alt="Odinbook profile page for Peter Parker" width="100%">


### Features

* **Real-time PBS data:** receive PBS information about your selected medication as your write the prescription. This includes criteria for PBS, max quantity/repeats, and authority information.
* **Active ingredient prescribing:** automatically adjust your prescription format to meet guidelines for active ingredient prescribing, including support for the List of Excluded Medicinal Items (LEMI) and the List of Medicinal Items for Brand Consideration (LMBC).
* **Instant re-prescribe:** save any scripts as 'favourites' for quick one-click re-prescribe functionality. Favourites include all medicine details, so just add patient details, and the script is done. Quick and easy.
* **Multiple prescribers:** OptomRx supports as many prescriber profiles as you need. Perfect for locum work, or those at a single practice only. Switch between prescriber details as needed for each script.
* **No patient data retention:** patient information is never saved on OptomRx. When you save a script, only non-identifiable information regarding medication and PBS details are retained. OptomRx was and is designed as a prescription writing tool, not a prescription database.

### Technologies used

* [React](https://reactjs.org/) - Front-end JS framework
* [Firebase](https://maven.apache.org/) - Back-end as a service (authentication, database, and hosting)
* [Styled components](https://styled-components.com/) - App-wide custom styling

## Usage

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Requirements

A valid Google Places API key is required for Google's autocomplete functionality.

### Installing

First, clone the repository

```
git clone git@github.com:daniel-moderiano/optom-rx.git
```

Inside the root directoy, install all dependencies with npm

```
npm install
```

Finally, use the following to spin up the project on a development server

```
npm start
```


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/daniel-moderiano/optom-rx/blob/main/LICENSE) file for details.  
Authored and maintained by Daniel Moderiano.

## Acknowledgments

The following resources were a great help throughout the development of OptomRx.

* [Copy & Paste CSS](https://copy-paste-css.com/)
* [Paginated Tables in React](https://dev.to/franciscomendes10866/how-to-create-a-table-with-pagination-in-react-4lpd)
* [Responsive Tables with CSS](https://css-tricks.com/making-tables-responsive-with-minimal-css/)
* [Web accessibility tutorials](https://www.w3.org/WAI/tutorials/)
* [The Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg)

Finally, a special thanks to Sarah Smoker for her invaluable design and UI/UX ideas, and endless QA testing.
