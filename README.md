# Engineering React Rebase Challenge solutions

The a couple of rebase should be done and git conflict should be resolved in the second rebasing.

## The steps


```
git fetch : All branchs of the origin are downloaded in local.
git checkout autoReview : autoReview branch will be created based on origin autoReview
git fetch
git checkout biologyToday

git rebase biologyToday : It will be done successfully without any errors.
git rebase autoReview : It will have the merge conflicted 2 files(App.js and App.test.js) and it should be resolved.
                        I have done it by VScode editor.
git rebase --continue : It will make a commit with the last commit name of autoReview
```

## The results
```
feat: add Biology Today article
feat: add Auto Review article
fiat lux
```