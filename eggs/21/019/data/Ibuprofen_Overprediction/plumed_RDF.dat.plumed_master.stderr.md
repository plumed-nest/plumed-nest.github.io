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
[runnervmgx7h7:09080] *** Process received signal ***
[runnervmgx7h7:09080] Signal: Aborted (6)
[runnervmgx7h7:09080] Signal code:  (-6)
[runnervmgx7h7:09080] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc305845330]
[runnervmgx7h7:09080] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc30589ec0c]
[runnervmgx7h7:09080] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc30584527e]
[runnervmgx7h7:09080] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc3058288ff]
[runnervmgx7h7:09080] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc305ca5ff5]
[runnervmgx7h7:09080] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc305cbb0da]
[runnervmgx7h7:09080] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc305ca5a55]
[runnervmgx7h7:09080] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc305ca5a6f]
[runnervmgx7h7:09080] [ 8] plumed_master(+0x146dd)[0x55b2025106dd]
[runnervmgx7h7:09080] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc30582a1ca]
[runnervmgx7h7:09080] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc30582a28b]
[runnervmgx7h7:09080] [11] plumed_master(+0x15365)[0x55b202511365]
[runnervmgx7h7:09080] *** End of error message ***
</pre>
{% endraw %}
