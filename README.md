# image_correct<br>
大学のゼミで扱った　歪み補正のためのコード<br>
calcCamera.pyで歪みを計算　tmpに角をマークした画像，　レンスの歪みをcsvで出力<br>
calibrate.py歪みを補正　でcsvを用いて元画像の歪みを消去　resultに歪み補正後の画像が出力される．<br>
root/<br>
　├ calcCamera.py（カメラの歪みを計算）<br>
　├calibrate.py （カメラの歪みを補正）<br>
　├ img/<br>
　│　└  サンプル画像 <br>
　│<br>
　├ tmp/<br>
　│　└  角検出画像<br>
　│　└  mtx.csv(内部パラメータ)<br>
　│　└  dist.csv(内部パラメータ)<br>
　│<br>
　├ result/<br>
　│　└  歪み補正後画像 <br>
　└<br>
