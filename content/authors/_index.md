---
cms_exclude: true

build:
  render: never
cascade:
  # Restore the publication lists reached by historical author URLs.
  # Question marks match periods in slugs without triggering Hugo's extension check.
  - build:
      render: always
    _target:
      kind: term
      path: '/authors/{a?-adkins,andrew-robb,b-j-mohler,c?-caudek,claudio-zito,hua-chun-sun,m?-maaroufi,min-susan-li,roberta-l?-klatzky,rolf-d-ulrich,ryan-canales,s?-h?-yeo,tianshu-liu,tonja-machulla,yitian-shao,yuting-ye}'
  - build:
      render: never
      list: always
---
