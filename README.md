# base3example-blog


git clone git@github.com:digital-cube/base3example-blog.git
cd base3example-blog

git submodule update --init --recursive

cd base3
git checkout dev_blog
cd -

cd blog
git checkout dev
cd -

cd users
git checkout dev_blog

cd mailser
git checkout dev_blog
