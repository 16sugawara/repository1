# first_repository
*目的*：githubの練習，Classの練習  
*中身*：TDDBC大阪2.0自動販売機問題のプログラム（ステップ1~7+応用2つ）

投入金と釣銭ストック，売り上げの仕様  
・insertされたお金はtmpストックに貯まる  
・insert→refundの場合，tmpストックを釣銭として返す  
・釣銭が払えるかどうかは，tmpストック＋釣銭ストックで判定する  
・購入が確定した場合，tmpストックの中身を釣銭ストックに回し，釣銭ストックで釣銭を払う  
・釣銭ストックの各硬貨（紙幣）の上限を10枚とし，オーバーした分を売上ストックに回す  
・売上ストックと純粋な売り上げ額は一致しないので，売上は別にカウントする  
