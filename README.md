# QIskit12

#参照サイト
#https://qiskit.org/documentation/locale/ja_JP/tutorials/simulators/2_device_noise_simulation.html



1.単一量子ビットゲートエラー 。単一量子ビットの脱分極(depolarizing)エラーと単一量子ビットの熱緩和(thermal relaxation)エラーで構成されています。
2. ２量子ビットゲートエラー。２量子ビットの脱分極エラーと、ゲートの両量子ビットでの単一量子ビット熱緩和エラーで構成されています。
3.単一量子ビット読み出しエラー は、個々の量子ビットの測定から得られる古典ビット値です。

4.ノイズ・シミュレーションを実行する際には、そのバックエンド用に回路を transpile することが 重要 です。これによって回路は、バックエンドに対して正しいノイズ・ベース・ゲート・セットに変換されます。
