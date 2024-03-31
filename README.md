# Adapt Vision CDN Example

This repository provides a straightforward example demonstrating how to integrate Adapt Vision into your web projects using a Content Delivery Network (CDN). By leveraging Adapt's CDN, you can easily incorporate Adapt Vision libraries and styles into your applications.

## Getting Started

These instructions will guide you through the setup process and show you how to run a basic example of Adapt Vision in a local development environment.

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js and npm (Node Package Manager). If you don't have Node.js installed, download it from [Node.js website](https://nodejs.org/).

### Installation

1. **Clone the repository**

   Start by cloning this repository to your local machine using Git.

   ```bash
   git clone https://github.com/a-dapt/vision-cdn-example.git
   cd vision-cdn-example
   ```

2. **Install dependencies**

   Run the following command in your terminal to install the necessary dependencies:

   ```bash
   npm install
   ```

3. **Add your license key**

   Open the `index.html` file in your favorite text editor and replace the placeholder with your actual Adapt Vision license key.

   ```html
   <script>
     document.addEventListener("DOMContentLoaded", function () {
       AdaptVision.vision("#app", {
         licenseKey: "YOUR_LICENSE_KEY_HERE", // <-- Replace with your license key
         showOptions: true, // Show / Hide options modal
       });
       AdaptVision.initialize();
     });
   </script>
   ```

### Running the Example

To serve the example locally and view it in your browser, run:

```bash
npx serve
```

Navigate to http://localhost:3000 in your web browser to see the example in action.
