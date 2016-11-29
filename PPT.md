%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Beamer Presentation
% LaTeX Template
% Version 1.0 (10/11/12)
%
% This template has been downloaded from:
% http://www.LaTeXTemplates.com
%
% License:
% CC BY-NC-SA 3.0 (http://creativecommons.org/licenses/by-nc-sa/3.0/)
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%	PACKAGES AND THEMES
%----------------------------------------------------------------------------------------

\documentclass{beamer}

\mode<presentation> {

% The Beamer class comes with a number of default slide themes
% which change the colors and layouts of slides. Below this is a list
% of all the themes, uncomment each in turn to see what they look like.

%\usetheme{default}
%\usetheme{AnnArbor}
%\usetheme{Antibes}
%\usetheme{Bergen}
%\usetheme{Berkeley}
%\usetheme{Berlin}
%\usetheme{Boadilla}
%\usetheme{CambridgeUS}
%\usetheme{Copenhagen}
%\usetheme{Darmstadt}
%\usetheme{Dresden}
\usetheme{Frankfurt}
%\usetheme{Goettingen}
%\usetheme{Hannover}
%\usetheme{Ilmenau}
%\usetheme{JuanLesPins}
%\usetheme{Luebeck}
%\usetheme{Madrid}
%\usetheme{Malmoe}
%\usetheme{Marburg}
%\usetheme{Montpellier}
%\usetheme{PaloAlto}
%\usetheme{Pittsburgh}
%\usetheme{Rochester}
%\usetheme{Singapore}
%\usetheme{Szeged}
%\usetheme{Warsaw}

% As well as themes, the Beamer class has a number of color themes
% for any slide theme. Uncomment each of these in turn to see how it
% changes the colors of your current slide theme.

%\usecolortheme{albatross}
%\usecolortheme{beaver}
%\usecolortheme{beetle}
%\usecolortheme{crane}
%\usecolortheme{dolphin}
%\usecolortheme{dove}
%\usecolortheme{fly}
%\usecolortheme{lily}
%\usecolortheme{orchid}
%\usecolortheme{rose}
%\usecolortheme{seagull}
%\usecolortheme{seahorse}
%\usecolortheme{whale}
%\usecolortheme{wolverine}

\setbeamertemplate{footline} % To remove the footer line in all slides uncomment this line
%\setbeamertemplate{footline}[page number] % To replace the footer line in all slides with a simple slide count uncomment this line

\setbeamertemplate{navigation symbols}{} % To remove the navigation symbols from the bottom of all slides uncomment this line
}

\usepackage{graphicx} % Allows including images
\usepackage{booktabs} % Allows the use of \toprule, \midrule and \bottomrule in tables

%----------------------------------------------------------------------------------------
%	TITLE PAGE
%----------------------------------------------------------------------------------------

\title[Short title]{Practical evaluation of Time Sensitive Networking using the TTTech Starter Kit} % The short title appears at the bottom of every slide, the full title is only on the title page

\author{Daniel A. Dzissah} % Your name
\institute[TITECH] % Your institution as it will appear on the bottom of every slide, may be shorthand to save space
{
Tokyo Institute of Technology \\ % Your institution for the title page
Obi Laboratory \\ % Your institution for the title page
\medskip
\textit{john@smith.com} % Your email address
}
\date{\today} % Date, can be changed to a custom date

\begin{document}

\begin{frame}
\titlepage % Print the title page as the first slide
\end{frame}

\begin{frame}
\frametitle{Overview} % Table of contents slide, comment this block out to remove it
\tableofcontents % Throughout your presentation, if you choose to use \section{} and \subsection{} commands, these will automatically be printed on this slide as an overview of your presentation
\end{frame}

%----------------------------------------------------------------------------------------
%	PRESENTATION SLIDES
%----------------------------------------------------------------------------------------

%------------------------------------------------
\section{First Section} % Sections can be created in order to organize your presentation into discrete blocks, all sections and subsections are automatically printed in the table of contents as an overview of the talk
%------------------------------------------------

\subsection{Subsection Example} % A subsection can be created just before a set of slides with a common theme to further break down your presentation into chunks

\begin{frame}
\frametitle{Paragraphs of Text}
Sed iaculis dapibus gravida. Morbi sed tortor erat, nec interdum arcu. Sed id lorem lectus. Quisque viverra augue id sem ornare non aliquam nibh tristique. Aenean in ligula nisl. Nulla sed tellus ipsum. Donec vestibulum ligula non lorem vulputate fermentum accumsan neque mollis.\\~\\

Sed diam enim, sagittis nec condimentum sit amet, ullamcorper sit amet libero. Aliquam vel dui orci, a porta odio. Nullam id suscipit ipsum. Aenean lobortis commodo sem, ut commodo leo gravida vitae. Pellentesque vehicula ante iaculis arcu pretium rutrum eget sit amet purus. Integer ornare nulla quis neque ultrices lobortis. Vestibulum ultrices tincidunt libero, quis commodo erat ullamcorper id.
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{Bullet Points}
\begin{itemize}
\item Lorem ipsum dolor sit amet, consectetur adipiscing elit
\item Aliquam blandit faucibus nisi, sit amet dapibus enim tempus eu
\item Nulla commodo, erat quis gravida posuere, elit lacus lobortis est, quis porttitor odio mauris at libero
\item Nam cursus est eget velit posuere pellentesque
\item Vestibulum faucibus velit a augue condimentum quis convallis nulla gravida
\end{itemize}
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{Blocks of Highlighted Text}
\begin{block}{Block 1}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer lectus nisl, ultricies in feugiat rutrum, porttitor sit amet augue. Aliquam ut tortor mauris. Sed volutpat ante purus, quis accumsan dolor.
\end{block}

\begin{block}{Block 2}
Pellentesque sed tellus purus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Vestibulum quis magna at risus dictum tempor eu vitae velit.
\end{block}

\begin{block}{Block 3}
Suspendisse tincidunt sagittis gravida. Curabitur condimentum, enim sed venenatis rutrum, ipsum neque consectetur orci, sed blandit justo nisi ac lacus.
\end{block}
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{Multiple Columns}
\begin{columns}[c] % The "c" option specifies centered vertical alignment while the "t" option is used for top vertical alignment

\column{.45\textwidth} % Left column and width
\textbf{Heading}
\begin{enumerate}
\item Statement
\item Explanation
\item Example
\end{enumerate}

\column{.5\textwidth} % Right column and width
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer lectus nisl, ultricies in feugiat rutrum, porttitor sit amet augue. Aliquam ut tortor mauris. Sed volutpat ante purus, quis accumsan dolor.

\end{columns}
\end{frame}

%------------------------------------------------
\section{Second Section}
%------------------------------------------------

\begin{frame}
\frametitle{Table}
\begin{table}
\begin{tabular}{l l l}
\toprule
\textbf{Treatments} & \textbf{Response 1} & \textbf{Response 2}\\
\midrule
Treatment 1 & 0.0003262 & 0.562 \\
Treatment 2 & 0.0015681 & 0.910 \\
Treatment 3 & 0.0009271 & 0.296 \\
\bottomrule
\end{tabular}
\caption{Table caption}
\end{table}
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{Theorem}
\begin{theorem}[Mass--energy equivalence]
$E = mc^2$
\end{theorem}
\end{frame}

%------------------------------------------------

\begin{frame}[fragile] % Need to use the fragile option when verbatim is used in the slide
\frametitle{Verbatim}
\begin{example}[Theorem Slide Code]
\begin{verbatim}
\begin{frame}
\frametitle{Theorem}
\begin{theorem}[Mass--energy equivalence]
$E = mc^2$
\end{theorem}
\end{frame}\end{verbatim}
\end{example}
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{Figure}
Uncomment the code on this slide to include your own image from the same directory as the template .TeX file.
%\begin{figure}
%\includegraphics[width=0.8\linewidth]{test}
%\end{figure}
\end{frame}

%------------------------------------------------

\begin{frame}[fragile] % Need to use the fragile option when verbatim is used in the slide
\frametitle{Citation}
An example of the \verb|\cite| command to cite within the presentation:\\~

This statement requires citation \cite{p1}.
\end{frame}

%------------------------------------------------

\begin{frame}
\frametitle{References}
\footnotesize{
\begin{thebibliography}{99} % Beamer does not support BibTeX so references must be inserted manually as below
\bibitem[Smith, 2012]{p1} John Smith (2012)
\newblock Title of the publication
\newblock \emph{Journal Name} 12(3), 45 -- 678.
\end{thebibliography}
}
\end{frame}

%------------------------------------------------

\begin{frame}
\Huge{\centerline{The End}}
\end{frame}

%----------------------------------------------------------------------------------------

\end{document} 


TSN性能評価 作業整理

16-11-25 E産業G 池田

このメモは、12/9のインターン成果報告および技術資料登録(技メモ想定)に向けて
10/3からのTSN性能評価の作業内容を整理したものである。
プロジェクトの背景・目的等

    2012年頃より、IEEE802.1委員会において、産業ネットワーク向けの低遅延・高精度時刻同期・高信頼(冗長化)などの
    新たなイーサネット技術群が議論され、TSN(Time-Sensitive Networking)として標準化が進められてきた。
    TSNは当社FAビジネスにおいても大きなインパクトがあると想定され、その技術を詳細に理解することが必要である。
    しかしながら、2016年11月現在、TSNの多くの技術はドラフト段階であり、製品に適用した場合の機能や性能について
    理解することが難しい状況であった。
    かかる状況のもと、TTTech社よりドラフト仕様を元にTSN技術の一部を実装したTSNスタータキットが販売された。
        販売されたのはいつだっけ？
    そこで、E産業GではこのTSNスタータキットを用い、性能面を中心にTSNの評価を行った。結果を報告する。

10/3からやったこと

    TSNの概要把握
        TSNドラフトと技術資料の調査
        詳細はリソースの1参照。
    TSNスタータキット調査
        マニュアルを読みながら実機を組み立てて何ができるか調査した。
        わかったこと
            TSNスイッチ×3とBeagle Bone Black(以下、BBB)×2からなるキット。
            TSNスイッチはIEEE1588v2(以下、PTPv2)とIEEE802.1Qbv、BBBはPTPv2のみサポート。

            キットは起動すると自動的にPTPv2で時刻同期。さらに、TSNスイッチは時刻同期に成功すると
            IEEE802.1Qbvの動作(フレームスケジューリング)を開始する。

                3.2 Getting Started
                The Pub/Sub demo application starts on the endpoints automatically after the power-up
                and requires no user action.

                3.3 Clock Synchronization
                All devices of the DEStarter Kit make use of a PTP clock synchronization also referred as 1588
                version 2. The clock synchronization is needed to establish a common time within the network. The
                configured TSN schedule is activated automatically in the switches, once the devices are
                successfully synchronized.

            BBBはOPC-UA PubSubパケットを双方向で送信する。これらのパケットはTSNトラフィックとして扱われる。
            また、BBBはTSNとして扱われないトラフィック(QoSトラフィック)も同時に送信する。

                3.4 OPC UA PubSub Demo Application
                The demo application starts automatically when the endpoints are powered up.
                These data sets are published periodically using
                TSN data flows and also using normal QoS Ethernet traffic to compare the performance.

                TSNトラフィックか否かはVLANで判断する

                    4.1 TSN configuration
                    The OPC UA PubSub nodes exchange critical data based on a VLAN configuration. This data is
                    transmitted using VLAN ID 3, Priority 5 and will be forwarded by the switch using standard rules.
                    The VLAN ID 3 is limited to the ports within the critical path in the network.

            BBBにはWebI/Fが用意されており、TSNとQoSトラフィックのレートをリアルタイムで測定可能。
            TSNスイッチとBBBのPTPv2の設定変更は極めて限定的。
                BBBのPTPv2実装はlinuxptp。マニュアルには記載無いが、linuxptpのコマンド群で
                priority2の変更や動作状態確認(例えばBMの認識状態)を行えることを確かめた。
                スイッチは設定も動作状態表示も基本的に不可
        課題

            WebI/Fの測定はS/Wで行うため精度が低い(課題1)

                5.1 Graphical Data Visualization - Web Interface
                ? TSN TS type (Tx/Rx): This value shows which kind of timestamp is used for TSN
                Streams to perform the measurements.
                ? SW: Software timestamp is used (kernel driver level)
                ? HW: Hardware timestamp is used
                ? QoS TS type (Tx/Rx): This value shows which kind of timestamp is used for QoS
                Streams to perform the measurements.
                ? SW: Software timestamp is used (kernel driver level)
                ? HW: Hardware timestamp is used

            BBBのデモアプリを含め、スタータキットは基本コンフィグ不可であり、条件を変えて測定ができない(課題2)。
                例えば、パケット長やレート。
                仮に変えられたとしても、レートはおそらくそんなに高くはならない。
            IEEE802.1Qbvのパラメータが分からない(課題3)
                マニュアルの4.1節にスケジュールダイアグラムがあるけれど、詳細が良く分からない
                ゲートオープンの時間、キューのマッピング等。
        対策
            課題1と2の対策: IXIAを使って性能測定する。
            課題3はTTTechに聞く。
    TSN性能評価
        方針
            IXIAをPTPv2サポート機器としてネットワークに参加させ、レイテンシを測定
        準備
            BBBが送信しているパケットを調べる
                IEEE4000を使ってミラーリングしてパケット解析。
                BBBはPTPv2と、239.0.0.1宛てのマルチキャストを送信していた。
                マルチキャストはVLAN ID=3 Prio.=5(TSN)とVLAN ID=3 Prio.=0(QoS)の二種類
                パケットデータは未調査だが、別途PCからUA Expertで見るに、トラフィックの統計情報の模様。
                OPC-UAプロセスも特定(Killしたらパケットがとまった)
            IXIAの使い方を調べる
                PTPv2エミュレーション機能はメンバも使った人がいないので、マニュアルをもとに調査し
                操作方法を確立。
        環境構築・測定
            SW-1のport4、SW-3のport3にIXIA-1と2を追加。さらに、noise-traffic(低優先パケット)用に
            IXIA-port3を追加(図を書くこと)。
                BBBは残す(外したらパケットが通らなくなった。スケジュールがアクティベートされない？)
                ただし、OPC-UAプロセスはkillしてパケットを止める。
            IXIA-1と2は双方向でパケットを送信し、スループットとレイテンシを測定。
                VLAN ID=3 Prio.=5(TSN)とVLAN ID=3 Prio.=0(QoS)の二種類でそれぞれ実施。
                パラメータを色々変える。測定パケットのパケット長やレート、さらにnoise-trafficのレート等。

        結果
        T.B.D.
        考察
            Qbvの効果は出ているか
                レートは低いが遅延は固定。noise-trafficに依らない。
            理論値との比較

                課題3が解決できていない問題があるが、そもそもどうやってQbvのスループットやレイテンシを
                算出するのか。→ A.I.詳しい人に聞くこと

                普通のQoSスイッチの算出との比較でもとりあえず良い？
            OPC-UAとTSNの連携
                OPC-UA Pub/Sub over TSNだが、スイッチ側ではOPC-UAかどうかは別に見ていないので
                実際連携はしていない。

インターン成果報告会に向けて

    インターンで苦労したこと、身についたこと
        技術面の他、生活や取り組み姿勢等も含む。
    ダニエルさんは今回の研究成果を自分の領域にどう活かすか
        ネットワークの評価技術は身についたはず。何か役立つ？
        PTPv2とかOPC-UAの適用はありうる？
        (大石さんの話では)TSNにはセキュリティの話題はまだ無い模様。
        一方、OPC-UA PubSubはドラフトにセキュリティの話題もある模様なので
        セキュリティに関する話をするならそちら？

リソース

    TSN/OPC-UA概要とTSNスタータキット調査のドキュメント(ダニエルさんのレポート)
    file:\\elfserve\nse$\Teams\E産業\社外秘\160_インターンシップ\FY16-3Q\00_file_sharing\40_Achievement\

    スタータキットのマニュアル
    file:\\elfserve\nse$\Teams\E制御\社外秘\common\1_起業費\2016\30_入着機材\TSN_スタータキット

