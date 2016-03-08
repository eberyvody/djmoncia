## useful
    alias push-djmoncia="aws s3 sync /Users/monica/Developer/djmoncia.com s3://djmoncia.com/ --delete --exclude '.git/*' --exclude '*.DS_Store' --exclude 'README.md'"
    alias dev-djmoncia="cd /Users/monica/Developer/djmoncia.com && (python -m SimpleHTTPServer 3000 &) && open -a Google\ Chrome http://localhost:3000"
