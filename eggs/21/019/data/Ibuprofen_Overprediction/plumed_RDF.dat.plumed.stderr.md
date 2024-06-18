**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action COM with label RDF_c284 : cannot understand the following words from the input line : RDF_c285:, COM, ATOMS=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402, RDF_c286:, COM, ATOMS=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435, RDF_c287:, COM, ATOMS=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468, RDF_c288:, COM, ATOMS=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501, RDF_g:, GROUP, ATOMS=RDF_c1,RDF_c2,RDF_c3,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288, RDF_d:, DISTANCES, GROUP=RDF_g, MORE_THAN=RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09, HISTOGRAM=TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01, PRINT, ARG=RDF_d.*, FILE=plumed_md_RDF.dat
[fv-az1272-851:09306] *** Process received signal ***
[fv-az1272-851:09306] Signal: Aborted (6)
[fv-az1272-851:09306] Signal code:  (-6)
[fv-az1272-851:09306] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb43b042520]
[fv-az1272-851:09306] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb43b0969fc]
[fv-az1272-851:09306] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb43b042476]
[fv-az1272-851:09306] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb43b0287f3]
[fv-az1272-851:09306] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb43b4a2b9e]
[fv-az1272-851:09306] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb43b4ae20c]
[fv-az1272-851:09306] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb43b4ae277]
[fv-az1272-851:09306] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb43b4ae52b]
[fv-az1272-851:09306] [ 8] plumed(+0x12f48)[0x55d460d3cf48]
[fv-az1272-851:09306] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb43b029d90]
[fv-az1272-851:09306] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb43b029e40]
[fv-az1272-851:09306] [11] plumed(+0x131e5)[0x55d460d3d1e5]
[fv-az1272-851:09306] *** End of error message ***
</pre>
{% endraw %}
