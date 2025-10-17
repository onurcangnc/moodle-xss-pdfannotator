# moodle-xss-pdfannotator
The Moodle PDF Annotator plugin’s Public Comments feature doesn’t sanitize user input before displaying it in the PDF viewer. This allows low-privileged users to store malicious JavaScript that executes automatically when others open the annotated document, causing XSS attacks.
