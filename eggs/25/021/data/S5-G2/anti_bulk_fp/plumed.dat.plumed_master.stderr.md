**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G2/anti_bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05097] *** Process received signal ***
[runnervmeorf1:05097] Signal: Aborted (6)
[runnervmeorf1:05097] Signal code:  (-6)
[runnervmeorf1:05097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9582045330]
[runnervmeorf1:05097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f958209eb2c]
[runnervmeorf1:05097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f958204527e]
[runnervmeorf1:05097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95820288ff]
[runnervmeorf1:05097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f95824a5ff5]
[runnervmeorf1:05097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f95824bb0da]
[runnervmeorf1:05097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f95824a5a55]
[runnervmeorf1:05097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f95824a5a6f]
[runnervmeorf1:05097] [ 8] plumed_master(+0x146dd)[0x557bacee16dd]
[runnervmeorf1:05097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f958202a1ca]
[runnervmeorf1:05097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f958202a28b]
[runnervmeorf1:05097] [11] plumed_master(+0x15365)[0x557bacee2365]
[runnervmeorf1:05097] *** End of error message ***
</pre>
{% endraw %}
