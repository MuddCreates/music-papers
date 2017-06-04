* [Crawford15]. *What Sounds So Good? Maybe, Time Will Tell.*



* [WangWang14] *Improving Content-based and Hybrid Music
  Recommendation using Deep Learning*

  Radon:

  > This seems like the state of the art. It also required a 15-node
  > GPU computing cluster, so maybe not quite yet for us.

* [ShaoLiOgihara08] *Quantify Music Artist Similarity Based on Style
  and Mood*

  Radon:

  > This uses collaborative filtering techniques to get a metric for
  > comparing *artists*, not songs. Content-based metrics are
  > introduced only as a comparison.

* [LiOgihara06]. *Towards Intelligent Music Information Retrieval*



* [PampalkFlexerWidmer05]. *Improvements of Audio-Based Music
  Similarity and Genre Classification*



* [LiOgiharaLi03]. *A Comparative Study on Content-Based Music Genre
  Classification*



* [Logan02] *Content-Based Playlist Generation: Exploratory
  Experiments*

  Radon (read it):

  > The naive way to generate a playlist from a seed song is to just
  > get the N closest songs. They instead try a couple of more
  > sophisticated techniques: tracing trajectories through the
  > song-similarity graph and implementing "automatic relevance
  > feedback" (results from an initial query are used to inform
  > further queries). Both of these don't perform as well as the
  > baseline. They find some improvement by using incorporating genre
  > information.
  >
  > I don't think their results present a problem for us. They
  > evaluate their results by looking at the homogeneity of the
  > playlist as a whole, which is not something we want. We just want
  > *local* similarity, with it being a good thing if the playlist
  > gradually drifts in style.

* [LoganSaloman01-MusicSimilarity] *A Music Similarity Function Based
  on Signal Analysis*

  Radon:

  > This appears to be an abbreviated version of
  > [LoganSalomon01-ContentBased].

* [LoganSalomon01-ContentBased] *A Content-Based Music Similarity
  Function*

  Radon (read it):

  > Determine the similarity between two pieces of music (e.g. MP3s)
  > based solely on their audio content. They split each song into a
  > sequence of 25ms frames, obtain a spectral measure (e.g. MFCCs),
  > cluster the frames by their spectral similarity, and use the
  > mean/covariance/weight of the largest clusters as the signature
  > for the song. Signatures are compared using EMD.
  >
  > To check their metric, they verify that songs in the same album
  > are more similar than random songs; that most similar songs are
  > likely to be from the same genre, artist, and album; that actual
  > users think songs rated as similar are actually similar; that
  > artists can be visualized in a sane way in Euclidean space; and
  > that the similarity metric is robust to clipping.
  >
  > The techniques seem within our reach if we can find some
  > appropriate libraries.

* [TzanetakisEsslCook01] *Automatic Musical Genre Classification Of
  Audio Signals*



* [FooteUchihasi01]. *The Beat Spectrum: A New Approach to Rhythm
  Analysis*



* [RubnerTomasiGuibas00]. *The Earth Mover's Distance as a Metric for
  Image Retrieval*



[Crawford15]: Crawford15.pdf
[FooteUchihasi01]: FooteUchihasi01.pdf
[LiOgihara06]: LiOgihara06.pdf
[LiOgiharaLi03]: LiOgiharaLi03.pdf
[Logan02]: Logan02.pdf
[LoganSaloman01-MusicSimilarity]: LoganSaloman01-MusicSimilarity.pdf
[LoganSalomon01-ContentBased]: LoganSalomon01-ContentBased.pdf
[PampalkFlexerWidmer05]: PampalkFlexerWidmer05.pdf
[RubnerTomasiGuibas00]: RubnerTomasiGuibas00.pdf
[ShaoLiOgihara08]: ShaoLiOgihara08.pdf
[TzanetakisEsslCook01]: TzanetakisEsslCook01.pdf
[WangWang14]: WangWang14.pdf
