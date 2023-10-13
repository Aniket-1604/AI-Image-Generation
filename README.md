# AI-Image-Generation
A full stack application developed using the MERN stack and OpenAI API to unveil the use of Generative AI

The Front end is constructed using React that is fully adaptable and creates 1024x1024 images by leveraging the OpenAI API, based on user-provided prompts.
Users have the option to select prompts manually or utilize a preset collection of 50 prompts via the "Surprise Me" feature.

The Back end is build using the Node.js runtime environement, Express framework and MongoDB as the Database and Cloudinary

Overview:

Enter a custom prompt, or click the "Surprise Me" button to choose a random prompt.
After the generation, the users can use the share button to share the image to community.
The image to be shared is uploaded to cloudinary, which is then fetched from the database to showcase it on the Home page.
The Homepage exhibits all the generated and shared images by different users.
Hover over an image to view the name of the creator and a download icon.
Click on the download icon to download the image to your device.

Tech Tools used in the entire project:

Front-end : HTML+CSS, JavaScript, ReactJS, Vite, Tailwind CSS
Back-end : Node.js, Express, MongoDB, OpenAI API, Cloudinary

Hosted on https://ai-image-generation-aniket1604.netlify.app/
