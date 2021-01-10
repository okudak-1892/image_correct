# image_correct
大学のゼミで扱った　歪み補正のためのコード
calcCamera.pyで歪みを計算　tmpに角をマークした画像，　レンスの歪みをcsvで出力
calibrate.py歪みを補正　でcsvを用いて元画像の歪みを消去　resultに歪み補正後の画像が出力される．
root/
　├ calcCamera.py（カメラの歪みを計算）
　├calibrate.py （カメラの歪みを補正）
　├ img/
　│　└  サンプル画像 
　│
　├ tmp/
　│　└  角検出画像
　│　└  mtx.csv(内部パラメータ)
　│　└  dist.csv(内部パラメータ)
　│
　├ result/
　│　└  歪み補正後画像 
　└
