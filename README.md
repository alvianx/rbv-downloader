# rbv-downloader

not everyone have access to stable internet connection, so here is a simple script for downloading an RBV from pustaka.ut.ac.id so everyone can study even when there's no internet conenction (and books cause it's heavy to carry around).

## usage

watch this video tutorial on how to use this script

1. login to your RBV at pustaka.ac.id
2. open the book you want to download
3. choose the module you want to download
4. open your browser console using F12
5. run this script below
`fetch('https://github.com/alvianx/rbv-downloader/scripts.js').then(response => response.text()).then(script => eval(script)).catch(err => console.error('Failed to load script:', err));`
6. wait a moment for the book to be downloaded
7. enjoy

for personal use only, all copyrights goes to UT as the publisher. 
