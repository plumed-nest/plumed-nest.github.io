**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : cannot understand the following words from the input line : RDF_c285:, COM, ATOMS=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402, RDF_c286:, COM, ATOMS=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435, RDF_c287:, COM, ATOMS=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468, RDF_c288:, COM, ATOMS=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501, RDF_g:, GROUP, ATOMS=RDF_c1,RDF_c2,RDF_c3,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288, RDF_d:, DISTANCES, GROUP=RDF_g, MORE_THAN=RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09, HISTOGRAM=TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01, PRINT, ARG=RDF_d.*, FILE=plumed_md_RDF.dat
[fv-az1112-175:66844] *** Process received signal ***
[fv-az1112-175:66844] Signal: Aborted (6)
[fv-az1112-175:66844] Signal code:  (-6)
[fv-az1112-175:66844] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47d4e45330]
[fv-az1112-175:66844] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47d4e9eb2c]
[fv-az1112-175:66844] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47d4e4527e]
[fv-az1112-175:66844] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47d4e288ff]
[fv-az1112-175:66844] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47d52a5ff5]
[fv-az1112-175:66844] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47d52bb0da]
[fv-az1112-175:66844] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47d52a5a55]
[fv-az1112-175:66844] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47d52a5a6f]
[fv-az1112-175:66844] [ 8] plumed_master(+0x146dd)[0x558deab266dd]
[fv-az1112-175:66844] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47d4e2a1ca]
[fv-az1112-175:66844] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47d4e2a28b]
[fv-az1112-175:66844] [11] plumed_master(+0x15365)[0x558deab27365]
[fv-az1112-175:66844] *** End of error message ***
</pre>
{% endraw %}
