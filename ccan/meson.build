sources += files([
    'ccan/hash/hash.c',
    'ccan/htable/htable.c',
    'ccan/ilog/ilog.c',
    'ccan/likely/likely.c',
    'ccan/list/list.c',
    'ccan/str/debug.c',
    'ccan/str/str.c',
    'ccan/strset/strset.c',
])

if get_option('buildtype') == 'debug'
    add_project_arguments('-DCCAN_LIST_DEBUG=1',  language : ['c', 'cpp'])
    add_project_arguments('-DCCAN_STR_DEBUG=1',  language : ['c', 'cpp'])
endif
