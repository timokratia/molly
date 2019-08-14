+++
title = "about"

template = "base.html"

[extra]
banner_quote = "The unlived life is not worth examining."
banner_footer = "...and other thoughts of mine."
+++

{{ section_begin(header="me") }}

Nullam eu ante vel est convallis dignissim{% sidenote(unique_id="convallis dignissim") %}This is a test sidenote.{% end %}.
Fusce suscipit, wisi nec facilisis facilisis, est dui fermentum leo, quis tempor ligula erat quis odio.
Nunc rutrum turpis sed pede.
Sed bibendum.Aliquam posuere.
Nunc aliquet, augue nec adipiscing interdum, lacus tellus malesuada massa, quis varius mi purus non odio.

Nullam eu ante vel est convallis dignissim{% sidenote(unique_id="convallis dignissim") %}This is a test sidenote.{% end %}.
Fusce suscipit, wisi nec facilisis facilisis, est dui fermentum leo, quis tempor ligula erat quis odio.
Nunc rutrum turpis sed pede.
Sed bibendum.Aliquam posuere.
Nunc aliquet, augue nec adipiscing interdum, lacus tellus malesuada massa, quis varius mi purus non odio.

{{ section_con(header="this site") }}

Nullam eu ante vel est convallis dignissim{% sidenote(unique_id="convallis dignissim") %}This is a test sidenote. This is a test sidenote. This is a test sidenote. This is a test sidenote. This is a test sidenote.{% end %}.
Fusce suscipit, wisi nec facilisis facilisis, est dui fermentum leo, quis tempor ligula erat quis odio.
Nunc rutrum turpis sed pede.
Sed bibendum.Aliquam posuere.
Nunc aliquet, augue nec adipiscing interdum, lacus tellus malesuada massa, quis varius mi purus non odio.

Nullam eu ante vel est convallis dignissim{% sidenote(unique_id="convallis dignissim") %}This is a test sidenote.{% end %}.
Fusce suscipit, wisi nec facilisis facilisis, est dui fermentum leo, quis tempor ligula erat quis odio.
Nunc rutrum turpis sed pede.
Sed bibendum.Aliquam posuere.
Nunc aliquet, augue nec adipiscing interdum, lacus tellus malesuada massa, quis varius mi purus non odio.

```clj
;; Some code examples in Clojure. This is a comment.

;; applying a function to every item in the collection
(map tufte-css blog-posts)
;;;; if unfamiliar, see http://www.lispcast.com/annotated-map

;; side-effecty loop (unformatted, causing text overflow) - from https://clojuredocs.org/clojure.core/doseq
(doseq [[[a b] [c d]] (map list (sorted-map :1 1 :2 2) (sorted-map :3 3 :4 4))] (prn (* b d)))

;; that same side-effecty loop, formatted
(doseq [[[a b] [c d]] (map list
                           (sorted-map :1 1 :2 2)
                           (sorted-map :3 3 :4 4))]
  (prn (* b d)))

;; If this proselytizing has worked, check out:
;; http://howistart.org/posts/clojure/1
```
