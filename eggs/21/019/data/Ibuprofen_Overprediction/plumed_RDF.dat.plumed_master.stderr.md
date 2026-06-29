**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_RDF.dat   
Download: [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action COM with label RDF_c284 : it was not possible to interpret atom name ...
[runnervmmklqx:09348] *** Process received signal ***
[runnervmmklqx:09348] Signal: Aborted (6)
[runnervmmklqx:09348] Signal code:  (-6)
[runnervmmklqx:09348] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0fcf845330]
[runnervmmklqx:09348] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0fcf89eb2c]
[runnervmmklqx:09348] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0fcf84527e]
[runnervmmklqx:09348] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0fcf8288ff]
[runnervmmklqx:09348] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0fcfca5ff5]
[runnervmmklqx:09348] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0fcfcbb0da]
[runnervmmklqx:09348] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0fcfca5a55]
[runnervmmklqx:09348] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0fcfca5a6f]
[runnervmmklqx:09348] [ 8] plumed_master(+0x146dd)[0x5631936296dd]
[runnervmmklqx:09348] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0fcf82a1ca]
[runnervmmklqx:09348] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0fcf82a28b]
[runnervmmklqx:09348] [11] plumed_master(+0x15365)[0x56319362a365]
[runnervmmklqx:09348] *** End of error message ***
</pre>
{% endraw %}
