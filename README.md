# Memories in the Cloud

### Store, Process, and Manage Data on Google Cloud (Photos)
Upload, resize, and manage your photos with user authentication and secure storage on Google Cloud.

This project demonstrates the use of Google Cloud Platform (GCP) services to build a simple yet scalable photo storage and management application. It showcases various cloud abilities, including:

* **Cloud Storage:** Securely store uploaded photos in a dedicated bucket.
* **Cloud Functions:** Triggered by Pub/Sub messages, process uploaded photos and perform tasks like resizing and thumbnail generation.
* **Pub/Sub:** Asynchronous messaging service for decoupling upload events and image processing tasks.
* **(Optional) Authentication and Authorization:** Integrate user authentication and authorization mechanisms for secure access control.

**Key Features:**

* Upload and store photos in the cloud.
* (Optional) Resize uploaded photos for faster loading.
* (Optional) Generate thumbnails for easier browsing.
* (Optional) Implement user authentication and authorization for secure access.

**Getting Started:**

1. **Prerequisites:**
    * A Google Cloud Platform project with billing enabled.
    * Basic understanding of GCP services and Python programming (or your chosen language).
2. **Clone the repository:**
    ```bash
    git clone https://github.com/ChetanThapliyal/Memories-in-the-Cloud.git
    ```
3. **Setup:**
    * Follow the instructions in the `SETUP.md` file to configure the project and set up GCP resources.
4. **Run the application:**
    * Refer to the `RUN.md` file for detailed instructions on deploying and running the application.

**Contributing:**

We welcome contributions to this project! Please refer to the `CONTRIBUTING.md` file for guidelines on how to contribute code, documentation, or other improvements.

**License:**

This project is licensed under the MIT License: LICENSE.

**Further Enhancements:**

This project serves as a starting point. You can further enhance it by:

* **Adding advanced image processing features:** Implement functionalities like cropping, rotating, or applying filters to photos.
* **Integrating with other GCP services:** Utilize Cloud Vision API for image analysis or Cloud CDN for faster image delivery.
* **Developing a user interface:** Build a web or mobile application for user interaction and photo management
