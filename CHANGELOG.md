<a name="2.1.3"></a>
# 2.1.3 (2017-03-08)

## Enhancements

Document how to use nginx to serve kopf so we do not need to run as ES plugin.  Add example nginx
configs.

## Bug Fixes

## Others

Minor tweak to allow kopf to work with ES > 2.x without the annoying alert about version too old.
I am using with ES v5.2.1 and all the tasks I need to do are working for me.  Let me know if you
find something not working.


<a name="1.4.3"></a>
# 1.4.3 (2014-12-08)


## Bug Fixes

- **SNAPSHOT:** Display list of indices from snapshot instead of list of current indices when restoring a snapshot
  ([https://github.com/lmenezes/elasticsearch-kopf/issues/211])
