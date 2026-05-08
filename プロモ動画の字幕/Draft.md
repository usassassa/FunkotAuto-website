# DJ1 

Funkotという音楽に特化した全自動のDJツールです
This is an automated DJ tool specialized for Funkot music.

アプリはAuto DJとCue Editorの２つに分かれています
The application is divided into two parts: Auto DJ and Cue Editor.

ご覧になっているのはAuto DJが動作している様子です
What you are seeing now is the Auto DJ in action.

本動画ではアプリの挙動や使い方を紹介しながら
While introducing the behavior and usage of the app in this video,

Funkotの仕組や課題、アプリの意義、販売方法を説明します
I will also explain the mechanics and challenges of Funkot, the purpose of this app, and how it will be sold.



# Cue

これはCueEditorの画面です
This is the Cue Editor screen.

左のボックスに楽曲ファイルをドラッグ＆ドロップ
Drag and drop your audio files into the left box.

曲名をクリックすると編集モードになります
Click on a track name to enter edit mode.

Play CueとMix Outのキューの位置から再生できます
You can start playback from the Play Cue and Mix Out cue positions.

波形は拡大ができます
The waveform can be zoomed in.

メトロノームで聴覚的にも ずれを確認できます
You can also verify the synchronization audibly using the metronome.

MixOutのキューはカウントダウンの声の後ですね
The Mix Out cue should be placed after the countdown vocal.

タイミングのずれは1小節なのでボタンで動かします
The timing is off by one bar, so adjust it using the button.

直観的な操作で簡単にキューを打てました
Cues can be easily set with intuitive controls.

他の楽曲でも試してみましょう
Let's try it with another track.

2曲目は1曲目と同様なのでFunkotについて説明します
The setup for the second track is similar, so I'll explain a bit about Funkot.

Funkotという音楽はDJユースに特化した音楽で
Funkot is a genre of music specifically tailored for DJ use.

BPMやイントロ・アウトロの構成が多くの楽曲で同一です
The BPM and the structure of the intro/outro are identical across many tracks.

そのため、ほぼすべての曲でmixが成立します
Because of this, you can successfully mix almost any two tracks together.

↑[Count In]機能で8拍前からプレビューしています
(We are previewing from 8 beats ahead using the [Count In] feature.)



キューの位置のオフセット調整が必要なケース
A case requiring cue offset adjustment.

楽曲の頭出しの余白によりCueの位置がずれています
The cue position is shifted due to silence at the beginning of the track.

メトロノームでズレが聞き取れるかと思います
You should be able to hear the offset with the metronome.

下のエリアからズレの数値を入力します
Input the offset value from the area below.

揃いました
It's synced.

曲の頭がずれているので、MixOutの位置もずれています
Since the beginning of the track is offset, the Mix Out position is also shifted.

ここでPlayCueと数値を同期するボタンを使用します
Here we use the button to synchronize the value with the Play Cue.

揃いました
It's synced.

小節単位の調整だけすればMixOutも完成です
Just adjust by bars, and the Mix Out is complete.




この曲もイントロのオフセットを揃えましょう
Let's align the intro offset for this track as well.

オフセットを同期し、Mix Outも確認すると・・・
After syncing the offset, let's check the Mix Out...

ビートが大きくずれていますね？
The beat is quite out of sync, isn't it?

これはFunkotの大きな特徴 downbeat によるものです
This is due to "downbeat", a defining characteristic of Funkot.

Funkotには曲のBPMが楽曲の途中で大きく下がり、
In Funkot, the BPM often drops significantly in the middle of a track,

別のジャンルのように変化する展開がしばしばあります
changing the style completely as if it were a different genre.

このあたりまではイントロのメトロノームが一致していますが
Up to this point, the metronome matches the intro,

BPMが変わってメトロノームが合わなくなります
but once the BPM changes, the metronome no longer aligns.

この特徴をフォローするためPlayCueとMixOutで
To accommodate this feature, the Play Cue and Mix Out

別々にオフセットを設定できるように設計されています
are designed so you can set their offsets independently.

BPMが下がってもFunkotはたいてい元のBPMに戻るので
Even if the BPM drops, Funkot usually returns to its original BPM,

イントロとアウトロの構成は変わりません
so the structure of the intro and outro remains consistent.

オフセット計算がdownbeatでズレた分を調整します
We will adjust the offset to account for the shift caused by the downbeat.

曲の音量を下げてメトロノームの強調ができます
You can lower the track volume to emphasize the metronome.

Count Inで2小節前からチェック
Checking from 2 bars before using Count In.

OK
OK.

ここまでのキューをいれたプレイリストを保存します
Now we will save the playlist with the cues set so far.

保存したプレイリストは”Auto DJ”で使用します
The saved playlist will be used in "Auto DJ".




# DJ2

## 1

Auto DJで先ほどキューを入れたファイルを読み込みます
Now, load the file we just added cues to into Auto DJ.

先ほどキューの編集をしていない楽曲名が暗いですね
Notice that the tracks without edited cues are grayed out.

キューを編集した楽曲のみ自動で選曲されます
Only the tracks with edited cues will be selected automatically.

FunkotのDJはBPMを+10%して行う文化があります
There is a culture in Funkot DJing to play tracks with a +10% BPM increase.

AutoDJでは中央上部でピッチを設定できます
In Auto DJ, you can set the pitch at the top center.

上部でTICKETが消費され時間制限タイマーが動きました
At the top, a TICKET has been consumed and the time limit timer has started.

サブスクライブでPREMIUMになれば無制限になります
If you subscribe and become PREMIUM, this becomes unlimited.

マスターの音量をマウスホイールで調整できます
You can adjust the master volume using the mouse wheel.

再生中のトラックの波形をクリックすると移動できます
Clicking on the waveform of the currently playing track allows you to seek.

MixOutの数秒前でロックがかかります
It locks a few seconds before the Mix Out point.

用意したキューの位置を参照して自動でmixを開始します
It automatically starts mixing based on the cue positions you prepared.

EQと縦フェーダーの状態も表示されます
The status of the EQ and channel faders are also displayed.

EQ制御はDJ SUMMER RANDCELさんの監修です
The EQ control logic was supervised by DJ SUMMER RANDCEL.

基礎的なmix手法の確認として活用いただけます
You can use this to learn and review fundamental mixing techniques.


## 2

ビートのわずかな同期ズレは自動検出で補正されます
Slight sync deviations in the beat are automatically detected and corrected.

また冒頭数秒の音量を測定し自動Gain調整がされています
Also, it measures the volume of the first few seconds and performs automatic Gain adjustment.

もしmixが上手くいかない楽曲があった場合、
If you have a track that doesn't mix well,

曲名の上エリアでEditフラグを外し選曲から除外できます
you can remove the Edit flag above the track name to exclude it from selection.

再生が終わると自動で次の曲がDeckに入ります
Once playback finishes, the next track is automatically loaded into the Deck.

プレイリストの順番に選曲がされていきます
Tracks are selected in the order they appear in the playlist.

曲順は右クリックメニューやボタンで入れ替える事ができます
You can change the track order using the right-click menu or buttons.

プレイリストは同時に２つ読み込めます
You can load two playlists simultaneously.

再生中の曲の次の曲が自動で選曲されるので、
Since the track following the currently playing one is automatically selected,

サブプレイリストは右クリックメニューから割り込みをします
you can interrupt the flow from the sub-playlist using the right-click menu.

割り込み後はサブの中で次番号の曲が自動選曲されます
After the interruption, the next track from the sub-playlist will be automatically selected.

PC複数のオーディオアウトプットがあれば選択もできるので
If your PC has multiple audio outputs, you can select which one to record/stream from,

DJmixの裏でキューを用意することも可能です
making it possible to prepare cues in the background while the DJ mix is playing.




Funkot DJは入手した音源を確認する際に、
When Funkot DJs check newly acquired tracks,

若干長い繋ぎしろのイントロアウトロと向き合う必要があり、
they have to deal with rather long intros and outros meant for mixing,

DJユースを意識してpitchを+10%で確認する手間もあり、
and they also have the hassle of checking them at +10% pitch for DJ use.

そういったいくつかの課題と向き合ってきました
We've been facing several of these challenges.

そんなFunkot DJへのユーティリティツールでもあり、
This application serves as a utility tool for such Funkot DJs,

新しいFunkotの向き合い方を提供できると考えています
and we believe it can offer a new way to experience Funkot.




## 3

本アプリはsetup feeとして ¥1,000- で販売し
The application itself is sold for a setup fee of ¥1,000,

アプリのPREMIUMモード月額 ¥500- とセット販売します
and is bundled with the PREMIUM mode subscription at ¥500/month.

スタートアップは¥1,500- からとなります
The starting price is ¥1,500.

動画配信のBGMや店舗・イベントの利用は別プランで
For use as BGM in video streams, stores, or events, we have a separate plan.

公開利用・商用利用を許諾するプランは ¥1,000- になります
The plan granting public and commercial use licenses is ¥1,000/month.

アプリ購入済みの人へsetup feeのないプランも用意
We also provide plans without the setup fee for users who have already purchased the app.

プラン未加入の状態でもある程度試せるようにしています
Even without a plan, we've designed it so you can test it out to a certain extent.

Streamingプランとの機能の違いが一つだけあり
There is only one functional difference in the Streaming plan:

ウォーターマークを自動で入れる機能が解禁されます
it unlocks the feature to automatically insert audio watermarks.

残念ながら音源のぶっこぬき・横流しがある界隈なので
Unfortunately, this is a scene where unauthorized ripping and leaking of tracks occurs,

Streamingプランでは配信用の保護機能が使えます
so the Streaming plan provides features to protect your broadcast.

ウォーターマークのチャイムは自分でカスタムできます
You can customize the watermark chime sound yourself.

鳴らす頻度などもコントロールできます
You can also control how frequently it sounds.

このアプリで世界にFunkotがより広がることを願います
We hope this app helps spread Funkot further across the world.