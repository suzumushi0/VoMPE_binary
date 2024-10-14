# VoMPE binary distribution.

![FFAE99B6C1EF50FD8A922F1B437EC7AE_snapshot_2 0x](https://github.com/user-attachments/assets/8400bf06-5033-4bca-ae5b-d93f7a27272c)

VoMPE (Voice over MIDI Polyphonic Expression) analyzes voice input and then outputs polyphonic MIDI notes based on formant frequencies representing voice characteristics.

The process of voice production can be modeled by the vibration of the vocal cords and the resonance of the vocal tract. In this case, the voice spectrum is the product of the vibration spectrum of the vocal cords and the frequency characteristics of the vocal tract. Thus, the frequency characteristics of the vocal tract are called the spectral envelope. And the resonant frequencies of the vocal tract, i.e., the peak frequencies of the spectral envelope, are called formant frequencies. These are widely used in speech analysis, synthesis, and coding.

VoMPE estimates the spectral envelope of voice input using Linear Prediction Coefficients and then finds the formant frequencies. The spectral envelope is divided into bands and one band corresponds to one MIDI channel. VoMPE outputs MIDI notes that reflect formant frequencies whose amplitude is maximum in the band.

VoMPE is provided as a VST 3 plug-in for digital audio workstations and supports 16KHz, 44.1KHz, and 48KHz sampling rates. OS environment is 64bit Windows 11. Refer to the following document for details.

https://suzumushi0.hatenablog.com/entry/VM/VM_EN

VoMPE (Voice over MIDI Polyphonic Expression) は，音声入力を分析し，音声の特徴を表すフォルマント周波数に基づいたポリフォニックの MIDI ノートを出力する．

音声の生成過程は，声帯による振動と声道による共振 (レゾナンス) によってモデル化できる．この場合，音声のスペクトルは，声帯による振動のスペクトルと声道の周波数特性の積となる．このため，声道の周波数特性はスペクトラルエンベロープ (Spectral envelope) と呼ばれる．また，音道の共振周波数，即ちスペクトラルエンベロープのピークとなる周波数，をフォルマント (Formant) 周波数と呼び，これらは音声の分析，合成，符号化で広く用いられている．

VoMPE は，線形予測係数 (Linear Prediction Coefficients: LPC) によって，音声入力のスペクトラルエンベロープを推定し，フォルマント周波数を求める．スペクトラルエンベロープは複数のバンド (周波数帯) に分割され，各バンドは MIDI チャネルに対応する．VoMPE は各バンドにおいて振幅が最大となるフォルマント周波数に対応した MIDI ノートを出力する．

VoMPE はディジタルオーディオワークステーションの VST 3 plug-in として提供され，16KHz, 44.1KHz, 48KHz のサンプリングレートをサポートしている．また，OS 環境は 64 bit の Windows 11以降となる．詳細は以下のドキュメントを参照．

https://suzumushi0.hatenablog.com/entry/VM/VM_JP

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> at no charge.

<img width="100" src="https://user-images.githubusercontent.com/67182469/130337395-b8ab38cd-e66e-4056-b441-49d33337410e.png">
VST is a registered trademark of Steinberg Media Technologies GmbH.

