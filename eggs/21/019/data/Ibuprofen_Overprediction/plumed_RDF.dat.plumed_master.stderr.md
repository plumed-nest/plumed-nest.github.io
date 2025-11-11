**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : it was not possible to interpret atom name ...
[runnervmw9dnm:12984] *** Process received signal ***
[runnervmw9dnm:12984] Signal: Aborted (6)
[runnervmw9dnm:12984] Signal code:  (-6)
[runnervmw9dnm:12984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff599045330]
[runnervmw9dnm:12984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff59909eb2c]
[runnervmw9dnm:12984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff59904527e]
[runnervmw9dnm:12984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5990288ff]
[runnervmw9dnm:12984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5994a5ff5]
[runnervmw9dnm:12984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5994bb0da]
[runnervmw9dnm:12984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5994a5a55]
[runnervmw9dnm:12984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5994a5a6f]
[runnervmw9dnm:12984] [ 8] plumed_master(+0x146dd)[0x5609e9f066dd]
[runnervmw9dnm:12984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff59902a1ca]
[runnervmw9dnm:12984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff59902a28b]
[runnervmw9dnm:12984] [11] plumed_master(+0x15365)[0x5609e9f07365]
[runnervmw9dnm:12984] *** End of error message ***
</pre>
{% endraw %}
