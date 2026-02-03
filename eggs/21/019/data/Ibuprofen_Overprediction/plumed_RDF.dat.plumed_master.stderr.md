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
[runnervmkj6or:07630] *** Process received signal ***
[runnervmkj6or:07630] Signal: Aborted (6)
[runnervmkj6or:07630] Signal code:  (-6)
[runnervmkj6or:07630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1862645330]
[runnervmkj6or:07630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f186269eb2c]
[runnervmkj6or:07630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f186264527e]
[runnervmkj6or:07630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18626288ff]
[runnervmkj6or:07630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1862aa5ff5]
[runnervmkj6or:07630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1862abb0da]
[runnervmkj6or:07630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1862aa5a55]
[runnervmkj6or:07630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1862aa5a6f]
[runnervmkj6or:07630] [ 8] plumed_master(+0x146dd)[0x56015a8056dd]
[runnervmkj6or:07630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f186262a1ca]
[runnervmkj6or:07630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f186262a28b]
[runnervmkj6or:07630] [11] plumed_master(+0x15365)[0x56015a806365]
[runnervmkj6or:07630] *** End of error message ***
</pre>
{% endraw %}
