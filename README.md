# H5
>大家好，我是朱杰，人称杰宝！

SELECT SUM(purchase_count) as got_num,(instock_count) as inventory_num,SUM(upshelf_count) as upshelf FROM `adn_pur_to_inv` WHERE `warehouse` LIKE '%' AND `sign_time` BETWEEN '2018-05-10 00:00:00' AND '2018-05-10 23:59:59' 


