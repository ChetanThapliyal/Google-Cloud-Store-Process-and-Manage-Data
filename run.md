# Running the Cloud Photo Organizer project:

## Prerequisites:

Complete the setup steps outlined in SETUP.md.

### Steps:

Start the Cloud Function:

Use the appropriate command (e.g., gcloud functions deploy process_image) to deploy the Cloud Function responsible for processing uploaded photos.
(Optional) Run locally:

You can develop and test the application locally using tools like a local emulator for Cloud Functions. Refer to the specific documentation for your chosen language and development environment.
Test the application:

Use tools like Postman or curl to simulate uploading photos and triggering the Pub/Sub message that activates the Cloud Function.

Verify that photos are uploaded to the Cloud Storage bucket and processed as expected (e.g., resized, thumbnails generated).

### Additional notes:

Ensure you have set the required environment variables before running the application.
Adjust commands and configurations based on your specific setup and chosen language.
Consider implementing continuous integration and deployment (CI/CD) pipelines for automated testing and deployment in production environments.