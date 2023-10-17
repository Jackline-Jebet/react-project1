<!---------------------------------------My Steps -------------------------------------------->
create react app:
Delete unnecesaries
Test App.js on browser
Create bare components with default (rfce) [Navbar,Footer,MenuList]
      App.js{
        = import all the pages, components  & routes from react-router-dom
        = create links and route paths to all pages inside Router>switch>
        = 
      }
      Navbar.js {
      = two divs (logo and nav-links)
      = create classnames (navbar, (leftSide, rightSide))
      = @navlinks = [home,about,menu,contact]
      = create hidelinks id for all the pages links
      = create a function for menu bar(toggleNavbar for hidelinks)
      = install material ui icons and import the icon (reorderIcon)

      = import {Link} from react-router-dom
      = import navbar css
      = import logo from assets/logoimg
      }
      Footer.js {
        = main div with className 'footer'
        = 2nd div with classname 'socialMedia'
        = under 2nd div create a p tag (&copy; 2023 pedrotechpizza.com)
        = import all socialmedia Icons(facebook,instagram,twitter) like InstagramIcon from 'material ui/InstagramIcon' individually
        = parse all the socialMedia icons individually inside the 2nd div ie < InstagramIcon/>
      }

Create bare pages [About,Menu,contact,Home]
       Home.js {
        = two divs(main-div and one dive inside main with headercontainer class)
        = create classnames ('home', headerContainer)
        = on the 2nd div add style = {{BackgroundImage: `url(${BannerImage})`}}
        = import BannerImage from '../assets/pizza.jpeg
        = create H1()
        = create p()
        = create button(ORDER NOW)
        = put button() inside Link tag with link to="/menu"
        = import {Link} from 'react-router-dom'
        = import Home.css
       }
create Assets and place images
Create styles to hold css foe each component
Create Helpers folder to hold json objects




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
