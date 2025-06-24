# DocuMint
DocuMint is a client-side document manage

DocuMint: Your Personal Document Fortress! 🛡️
Tired of digital clutter? Lost in a sea of PDFs and scattered files? Welcome to DocuMint, your browser-based personal fortress for all things documents! Organize, manage, and tame your digital paperwork with ease, all while keeping your files safely on your local machine. No clouds, no servers, just pure, unadulterated document zen.

✨ Features That Make Life Easier:
Local Storage Magic: Pick any folder on your computer, and DocuMint transforms it into your secure document Mint. Your files stay your files, right where you want them.

Intuitive Dashboard: See all your important documents at a glance. Sort by name, date, or size to find what you need, fast!

"Files in Folder" View: Ever wonder what's lurking in your chosen folder that DocuMint isn't managing? Now you know! See untracked files and import them with a single click.

Bucket System: Create custom "buckets" (folders, but cooler!) to categorize your documents. Think "Q1 Expenses," "Medical Records 2024," or "My Secret Llama Fan Art."

Tag, You're It!: Add tags to documents for granular organization. Searching for "invoice" from "2023" for "Acme Corp"? Easy peasy!

PDF Powerhouse:

Combine PDFs: Merge multiple PDF files into one glorious super-PDF.

Compress PDFs: Shrink those bulky PDFs (using pdf-lib's magic useObjectStreams) to save space.

Quick PDF Preview: Double-click any PDF card to open it in a new browser tab instantly!

File Details at a Glance: Click the little "eye" icon to pop open a modal with all the juicy details: file name, type, size, date, bucket, tags, and even bill amount/currency (if you add it!). Click anywhere outside to make it disappear like digital ninja smoke.

Smart Selection Bar: Select multiple documents to perform bulk actions: download, combine, compress, delete. Efficiency is our middle name!

Trash Talk: Accidentally delete something? No worries, it goes to the Trash. Restore it or permanently delete it later. (Yes, multi-select works in trash too!)

Persistent Storage: Once you select your Mint folder, DocuMint remembers it (thanks, IndexedDB!). No more re-selecting on every reload.

Sleek & Responsive UI: Looks great on any device, from your desktop behemoth to your tiny phone screen.

🚀 How to Get Started (It's Super Easy!):
Open index.html: Simply open the index.html file in a modern web browser (like Chrome, Edge, Firefox, or Brave).

Select Your Mint: Click the "Select Storage Folder" button on the welcome screen. Choose a directory on your computer where you want DocuMint to store and manage your files. This is your personal Mint!

Upload & Organize:

Click "Upload Files" to add new documents.

Drag and drop files directly into the upload area.

Use the "Files in Folder" section in the sidebar to discover and import existing files from your Mint.

Edit document details, add tags, assign to buckets.

Explore & Manage:

Use the sidebar to navigate between your Dashboard, Important files, Buckets, and Trash.

Search for documents using the search bar.

Switch between grid and list views.

Select multiple files to perform bulk operations using the handy bar at the bottom.

Double-click a PDF to open it in a new tab.

Click the "eye" icon for detailed file information.

⚠️ Important Notes:
Browser Compatibility: DocuMint relies on the File System Access API, which is supported by most modern Chromium-based browsers (Chrome, Edge, Brave, Opera) and Firefox. Safari support is still developing.

Permissions: The browser will ask for your permission to read and write to your selected folder. This is crucial for DocuMint to function. Rest assured, your files do not leave your local machine.

No Cloud Sync: This is a purely local application. Your documents are stored only on your computer, not synced to any external service.

PDF Compression: While pdf-lib does a great job with compression, the actual size reduction depends on the original PDF's content (e.g., highly optimized PDFs might not shrink much further).

🛠️ Tech Under the Hood:
HTML, CSS, JavaScript: The core building blocks of the web!

File System Access API: The superpower enabling local file interaction.

PDF-Lib: For all the magical PDF manipulations.

JSZip: For creating those satisfying ZIP archives.

FileSaver.js: To make downloading files a breeze.

Font Awesome: For all the lovely icons.

IndexedDB: To remember your chosen storage folder.

DocuMint is designed to be a simple, effective, and privacy-respecting tool for your personal document management needs. Enjoy a clutter-free digital life!

Happy Organizing! 📂✨
