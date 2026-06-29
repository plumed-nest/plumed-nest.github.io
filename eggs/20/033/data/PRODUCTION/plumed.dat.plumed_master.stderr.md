**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0, REF1, REF2
[runnervmmklqx:09479] *** Process received signal ***
[runnervmmklqx:09479] Signal: Aborted (6)
[runnervmmklqx:09479] Signal code:  (-6)
[runnervmmklqx:09479] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcadb045330]
[runnervmmklqx:09479] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcadb09eb2c]
[runnervmmklqx:09479] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcadb04527e]
[runnervmmklqx:09479] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcadb0288ff]
[runnervmmklqx:09479] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcadb4a5ff5]
[runnervmmklqx:09479] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcadb4bb0da]
[runnervmmklqx:09479] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcadb4a5a55]
[runnervmmklqx:09479] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcadb4a5a6f]
[runnervmmklqx:09479] [ 8] plumed_master(+0x146dd)[0x56388ab196dd]
[runnervmmklqx:09479] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcadb02a1ca]
[runnervmmklqx:09479] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcadb02a28b]
[runnervmmklqx:09479] [11] plumed_master(+0x15365)[0x56388ab1a365]
[runnervmmklqx:09479] *** End of error message ***
</pre>
{% endraw %}
