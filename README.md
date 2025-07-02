# DocuMint 📂

**Your Personal Document Fortress - Client-Side Document Manager**  
DocuMint is a browser-based document management system that organizes files locally using modern web APIs. No cloud services, no servers – just pure client-side document zen.

![Demo](https://via.placeholder.com/800x400?text=DocuMint+UI+Screenshot)  
*Example interface - actual UI may vary*

## ✨ Key Features

### 🗂️ Core Functionality
- **Local Storage**: Directly manage files in any folder on your computer
- **IndexedDB**: Persists your selected storage location between sessions
- **File System API**: Secure read/write access to your local filesystem
- **Responsive UI**: Works seamlessly on desktop and mobile devices

### 📄 Document Management
- **Bucket System**: Create custom categories (e.g., "Tax Documents", "Medical Records")
- **Tagging**: Add custom tags for advanced organization
- **Import System**: Add existing files from your storage folder
- **Trash System**: Restore accidentally deleted files

### 🛠️ PDF Operations
- **Combine PDFs**: Merge multiple PDFs into one
- **Compress PDFs**: Reduce file size using `pdf-lib` optimizations
- **Preview**: Double-click to open PDFs in new tabs
- **Thumbnail Generation**: Automatic previews for image files

### ⚡ Productivity Tools
- **Smart Selection**: Bulk actions on multiple files
- **Important Flag**: Star critical documents for quick access
- **Sort & Filter**: Organize by name, date, or size
- **Search**: Full-text search across documents and tags

## 🚀 Getting Started

### Prerequisites
- Modern browser (Chrome/Edge ≥86, Firefox ≥78)
- File System Access API support
- Enable local file permissions when prompted

### Installation
```bash
git clone https://github.com/yourusername/documint.git
cd documint
# No build required - just open index.html!
