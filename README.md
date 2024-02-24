
# Install

```
npm install petpet-gen
```
# Example Usage

```javascript

const generateGif = require('petpet-gen');

// Define the URL of the avatar image you want to use
const avatarURL = 'URL_TO_YOUR_AVATAR_IMAGE';

// Define options for generating the GIF (optional)
const options = {
    resolution: 128,
    delay: 20,
    backgroundColor: null,
};

// Call the generateGif function with the avatar URL and options
generateGif(avatarURL, options)
    .then(gifData => {
        // Now you can use the generated GIF data as needed
        console.log('Generated GIF data:', gifData);
    })
    .catch(error => {
        // Handle any errors that occur during GIF generation
        console.error('Error generating GIF:', error);
    });
```

Replace 'URL_TO_YOUR_AVATAR_IMAGE' with the actual URL of the avatar image you want to use. You can also customize the options object according to your preferences.
