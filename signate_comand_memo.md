2021/04/24 新規作成
signateで使うコマンドラインでの操作


■signateパッケージのインストール
    $pip install signate

■トークンのダウンロード
    signateのHPからアカウント情報へ進みAPIトークンのダウンロードをする
    そのとき保存先は、C:\Users\XXX/.signate/　配下に保存する。
■やっているコンペの一覧取得
    $signate list
    一番左の列がコンペIDになっている
■提供データの取得
    signate files --competition-id=コンペID
■データセットをダウンロード
    signate download --competition-id=コンペID
    カレントディレクトリに保存される
■１ファイルずつダウンロード
    signate download --competition-id=コンペID --file-id=ファイルID --path=保存先ディレクトリのパス
■コンペにファイルを提出
    signate submit --competition-id=コンペID 提出ファイルのパス







