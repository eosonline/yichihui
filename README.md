pm2 start bin/www --watch --ignore-watch="config public" 
$.router.loadPage("#product_list_col")
draw_goods_col(all_goods.filter(function(item){return item.cat_id==101}))
draw_cats_col(cat.filter(function(item){return item.parent_id==1}))