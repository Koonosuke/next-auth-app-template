[...nextauth]→ キャッチオールセグメント
後続のセグメントをすべてキャッチする
Route Example URL params
pages/shop/[...slug].js /shop/a { slug: ['a'] }
pages/shop/[...slug].js /shop/a/b { slug: ['a', 'b'] }
pages/shop/[...slug].js /shop/a/b/c { slug: ['a', 'b', 'c'] }
