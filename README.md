cloudfiles-haproxy
==================

Haproxy

## Upgrading
wget new version
rm -rf CHANGELOG contrib/ doc/ ebtree/ examples/ include/ LICENSE Makefile Makefile.bsd Makefile.osx README ROADMAP src/ SUBVERS tests/ TODO VERDATE VERSION
tar -zxvf the.gz
mv haproxy-someversion/* .
update debian/changelog
