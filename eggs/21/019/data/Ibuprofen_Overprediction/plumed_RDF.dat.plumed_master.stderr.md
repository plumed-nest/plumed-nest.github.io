**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
(download [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action COM with label RDF_c284 : cannot understand the following words from the input line : RDF_c285:, COM, ATOMS=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402, RDF_c286:, COM, ATOMS=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435, RDF_c287:, COM, ATOMS=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468, RDF_c288:, COM, ATOMS=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501, RDF_g:, GROUP, ATOMS=RDF_c1,RDF_c2,RDF_c3,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288, RDF_d:, DISTANCES, GROUP=RDF_g, MORE_THAN=RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09, HISTOGRAM=TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01, PRINT, ARG=RDF_d.*, FILE=plumed_md_RDF.dat
[fv-az95-172:34738] *** Process received signal ***
[fv-az95-172:34738] Signal: Aborted (6)
[fv-az95-172:34738] Signal code:  (-6)
[fv-az95-172:34738] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbef9c37210]
[fv-az95-172:34738] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbef9c3718b]
[fv-az95-172:34738] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbef9c16859]
[fv-az95-172:34738] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbef9e9e911]
[fv-az95-172:34738] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbef9eaa38c]
[fv-az95-172:34738] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbef9eaa3f7]
[fv-az95-172:34738] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fbef9eaa6fd]
[fv-az95-172:34738] [ 7] plumed_master(+0xf5b5)[0x55adc4e415b5]
[fv-az95-172:34738] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbef9c180b3]
[fv-az95-172:34738] [ 9] plumed_master(+0xf8be)[0x55adc4e418be]
[fv-az95-172:34738] *** End of error message ***
</pre>
{% endraw %}
