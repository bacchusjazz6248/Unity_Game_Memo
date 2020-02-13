# Unity3D Memo
Unity3Dのゲーム作成時の問題点・解決法のメモ  
### 1. 地面の作成  
    1. 「3D Object」→「Terrain」で地面を作成出来る.
### 2. UnityちゃんをSceneに登場させる
  1. Unityちゃんのプレハブ「unitychan.prefab」をD & D.
  2. 「GameObject」→「Break Prefab Instance」でprefabから切り離す.
  3. 好きな場所にUnityちゃんを移動.
### 3. Unityちゃんのアニメーション設定
  1. 「UnityChanLocomotions.Controller」をUnityChanのInspector内のAnimatorのControllernに適応する.
  2. 「UnityChanControlScriptWithRgidBody」コンポーネントを追加.
  3. いい感じにCapsleColliderを調節.
  4. 「UnityChanControlScriptWithRgidBody」のOnGUIを削除(邪魔なので).
  5. RigidBodyのFreezeRotationのチェックをxyz全部つける(他のオブジェクトと接触した際に吹っ飛ばされないようにする).
### 4.モンスターの配置・アニメーション
