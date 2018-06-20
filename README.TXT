README_ja

ユニティちゃんトゥーンシェーダー Ver.2.0

「ユニティちゃんトゥーンシェーダー」は、セル風3DCGアニメーションの制作現場での要望に応えるような形で設計された、映像志向のトゥーンシェーダーです。

ユニティちゃんトゥーンシェーダーVer.2.0では、従来の機能に加えて大幅な機能強化を行いました。
Ver.1.0でできる絵づくりをカバーしつつ、さらに高度なルックが実現できるようになっています。

【ターゲット環境】
Unity5.6.x もしくはそれ以降が必要です。
※Nintendo Switchに対応した結果、Unity5.5.xで利用する場合、シェーダーにエラー表示が出ますが、動作上は問題はありません。

New!【iOS/OSX METALで使用する際の注意】
iOS/OSX METALで使用する場合、CullMode=OFF（両面表示）の時に、正しい表示が出来ない場合があります。
その場合、メッシュを両面に貼って、それぞれにCullMode=Back（背面カリング）/CullMode=Front（正面カリング）のマテリアルを設定するようにしてください。

【提供ライセンス】
「ユニティちゃんトゥーンシェーダーVer.2.0」は、UCL2.0（ユニティちゃんライセンス2.0）で提供されます。
ユニティちゃんライセンスについては、以下を参照してください。
http://unity-chan.com/contents/guideline/


【修正履歴】

2017/06/25：2.0.3：マニュアル修正。【iOS/OSX METALで使用する際の注意】を追加。
2017/06/19：2.0.3：Set_HighColorMask、Set_RimLightMaskの追加。機能強化の結果、Set_HighColorPositionは廃止。
2017/06/09：2.0.2：Nintendo Switch、PlayStation 4に正式対応。モバイル軽量版の追加。その他機能強化。
2017/05/20：2.0.1：TransClipping系シェーダーのブレンド仕様変更とリムライトに調整機能追加。
　　　　　　　　　 上の仕様変更に伴い、トランスペアレント系シェーダーを２つ追加。
　　　　　　　　　（ToonColor_DoubleShadeWithFeather_Transparent、ToonColor_ShadingGradeMap_Transparent）
2017/05/07：2.0.0：最初のバージョン


最新バージョン：2.0.3
最終リリース日：2017.06.25
カテゴリー：3D
形式：zip


//------------------------------
README_en

Unity-Chan Toon Shader Ver.2.0

Unity-Chan Toon Shader is a toon shader for images and video that is designed to meet your needs when creating cel-shaded 3DCG animations.

We have greatly enhanced performance in Unity-Chan Toon Shader Ver. 2.0.
It still has the same rendering capabilities as Ver. 1.0, but you can now create an even more sophisticated look.

【Target Environment】
Require Unity 5.6.x or later.
※As a result responding to Nintendo Switch platform, if using with Unity 5.5.x, some errors(warnings) appear in the shader, but there is no problem in operation.

New!【Using with iOS/OSX METAL】
When using with iOS / OSX METAL, correct display may not be possible when CullMode = OFF (double-sided drawing).
In that case, make the meshes on both sides and set materials of CullMode = Back (back-face culling) / CullMode = Front (front-face culling) for each.

【License】
Unity-Chan Toon Shader 2.0 is provided under the Unity-Chan License 2.0 terms.
Please refer to the following link for information regarding the Unity-Chan License.
http://unity-chan.com/contents/guideline/

Latest Version: 2.0.3
Update: 2017.06.25
Category: 3D
File format: zip
