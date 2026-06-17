AWS S3 deployment for the Elevate AI Solutions project landing page

Bucket used in Shani's screenshot:
  eais-projects-shani

Recommended object layout:
  s3://eais-projects-shani/index.html
  s3://eais-projects-shani/assets/Elevate_AI_Solutions_Logo.jpg
  s3://eais-projects-shani/assets/EAIS_animated_logo_zoom_out.mp4
  s3://eais-projects-shani/assets/project-clinic-intake.png
  s3://eais-projects-shani/assets/project-dashboard.png
  s3://eais-projects-shani/assets/project-databricks-etl.png

Important:
- The included index.html expects the filenames above exactly.
- Shani already uploaded the MP4 to S3. It is referenced but not included in this ZIP.
- If the video does not play, verify the MP4 object is public/readable and has Content-Type: video/mp4.
- If images do not show, verify object permissions and capitalization/spelling.
- If using direct S3 object URLs, the landing page should be:
  https://eais-projects-shani.s3.us-west-2.amazonaws.com/index.html

GitHub links used in the project cards:
  https://github.com/MariniaGroup/clinic-intake-case-study
  https://github.com/MariniaGroup/databricks-etl-pipeline
  https://github.com/MariniaGroup
