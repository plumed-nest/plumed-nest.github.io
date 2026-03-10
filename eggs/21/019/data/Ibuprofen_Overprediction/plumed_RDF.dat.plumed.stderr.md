**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : cannot understand the following words from the input line : RDF_c285:, COM, ATOMS=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402, RDF_c286:, COM, ATOMS=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435, RDF_c287:, COM, ATOMS=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468, RDF_c288:, COM, ATOMS=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501, RDF_g:, GROUP, ATOMS=RDF_c1,RDF_c2,RDF_c3,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288, RDF_d:, DISTANCES, GROUP=RDF_g, MORE_THAN=RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09, HISTOGRAM=TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01, PRINT, ARG=RDF_d.*, FILE=plumed_md_RDF.dat
[runnervm0kj6c:09575] *** Process received signal ***
[runnervm0kj6c:09575] Signal: Aborted (6)
[runnervm0kj6c:09575] Signal code:  (-6)
[runnervm0kj6c:09575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa23b445330]
[runnervm0kj6c:09575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa23b49eb2c]
[runnervm0kj6c:09575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa23b44527e]
[runnervm0kj6c:09575] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa23b4288ff]
[runnervm0kj6c:09575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa23b8a5ff5]
[runnervm0kj6c:09575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa23b8bb0da]
[runnervm0kj6c:09575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa23b8a5a55]
[runnervm0kj6c:09575] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa23b8a5a6f]
[runnervm0kj6c:09575] [ 8] plumed(+0x146dd)[0x55d0899f46dd]
[runnervm0kj6c:09575] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa23b42a1ca]
[runnervm0kj6c:09575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa23b42a28b]
[runnervm0kj6c:09575] [11] plumed(+0x15365)[0x55d0899f5365]
[runnervm0kj6c:09575] *** End of error message ***
</pre>
{% endraw %}
