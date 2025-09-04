**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10074] *** Process received signal ***
[pkrvm7jw40e0xgp:10074] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10074] Signal code:  (-6)
[pkrvm7jw40e0xgp:10074] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f608f445330]
[pkrvm7jw40e0xgp:10074] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f608f49eb2c]
[pkrvm7jw40e0xgp:10074] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f608f44527e]
[pkrvm7jw40e0xgp:10074] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f608f4288ff]
[pkrvm7jw40e0xgp:10074] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f608f8a5ff5]
[pkrvm7jw40e0xgp:10074] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f608f8bb0da]
[pkrvm7jw40e0xgp:10074] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f608f8a5a55]
[pkrvm7jw40e0xgp:10074] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f608f8a5a6f]
[pkrvm7jw40e0xgp:10074] [ 8] plumed_master(+0x146dd)[0x55bc027346dd]
[pkrvm7jw40e0xgp:10074] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f608f42a1ca]
[pkrvm7jw40e0xgp:10074] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f608f42a28b]
[pkrvm7jw40e0xgp:10074] [11] plumed_master(+0x15365)[0x55bc02735365]
[pkrvm7jw40e0xgp:10074] *** End of error message ***
</pre>
{% endraw %}
