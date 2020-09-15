---
data:
  _extendedDependsOn:
  - icon: ':heavy_check_mark:'
    path: examples/python/union_find.py
    title: examples/python/union_find.py
  _extendedRequiredBy: []
  _extendedVerifiedWith: []
  _pathExtension: py
  _verificationStatusIcon: ':heavy_check_mark:'
  attributes:
    PROBLEM: https://onlinejudge.u-aizu.ac.jp/courses/library/3/DSL/all/DSL_1_A
    links:
    - https://onlinejudge.u-aizu.ac.jp/courses/library/3/DSL/all/DSL_1_A
  bundledCode: "Traceback (most recent call last):\n  File \"/opt/hostedtoolcache/Python/3.8.5/x64/lib/python3.8/site-packages/onlinejudge_verify/documentation/build.py\"\
    , line 70, in _render_source_code_stat\n    bundled_code = language.bundle(stat.path,\
    \ basedir=basedir).decode()\n  File \"/opt/hostedtoolcache/Python/3.8.5/x64/lib/python3.8/site-packages/onlinejudge_verify/languages/python.py\"\
    , line 84, in bundle\n    raise NotImplementedError\nNotImplementedError\n"
  code: "# verify-helper: PROBLEM https://onlinejudge.u-aizu.ac.jp/courses/library/3/DSL/all/DSL_1_A\n\
    import sys\ninput = sys.stdin.buffer.readline\n\nfrom examples.python.union_find\
    \ import UnionFindTree\n\n\ndef main() -> None:\n    N, Q = map(int, input().split())\n\
    \    uft = UnionFindTree(N)\n    for _ in range(Q):\n        t, u, v = map(int,\
    \ input().split())\n        if t == 0:\n            uft.unite(u, v)\n        else:\n\
    \            print(int(uft.is_same(u, v)))\n\n\nif __name__ == \"__main__\":\n\
    \    main()\n"
  dependsOn:
  - examples/python/union_find.py
  isVerificationFile: true
  path: examples/python/union_find_aoj.test.py
  requiredBy: []
  timestamp: '2020-08-09 17:15:45+09:00'
  verificationStatus: TEST_ACCEPTED
  verifiedWith: []
documentation_of: examples/python/union_find_aoj.test.py
layout: document
redirect_from:
- /verify/examples/python/union_find_aoj.test.py
- /verify/examples/python/union_find_aoj.test.py.html
title: examples/python/union_find_aoj.test.py
---