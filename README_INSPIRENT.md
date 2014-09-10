SPECIAL INSTRUCTIONS FOR MY FRIENDS AT INSPIRENT
================================================


Quick Start Guide
-----------------

1. Add comments to your API source code.

2. Download and build the generator (one time):
    `git clone https://github.com/yvasiyarov/swagger.git $GOPATH/src/github.com/yvasiyarov/swagger`
    `cd $GOPATH/src/github.com/yvasiyarov/swagger`
    `git remote add polyglot-jones https://github.com/polyglot-jones/swagger`
    `git fetch polyglot-jones`
    `git checkout Inspirent-Special`
    `go install`

(After a while things will settle down and we won't need the Inspirent-Special branch anymore.)

3. To run, use the update_swagger.sh script in your project. It will generate both a MarkDown version (\*.md) and a Confluence version (\*.CONFLUENCE).

4. Commit the MarkDown version to github.

5. Use the Confluence version to update the Confluence page.

