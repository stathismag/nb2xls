- To release a new version of nb2xls on PyPI:

Update __meta__.py (set release version, remove 'dev')

git add the __meta__.py file and git commit

delete dist folder

`python setup.py sdist`

`twine upload dist/*`

git add and git commit

`git tag -a X.X.X -m 'comment'`

`git push`

`git push --tags`
