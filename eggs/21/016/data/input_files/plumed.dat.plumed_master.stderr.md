**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT
[runnervmeorf1:10151] *** Process received signal ***
[runnervmeorf1:10151] Signal: Aborted (6)
[runnervmeorf1:10151] Signal code:  (-6)
[runnervmeorf1:10151] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe2a9445330]
[runnervmeorf1:10151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe2a949eb2c]
[runnervmeorf1:10151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe2a944527e]
[runnervmeorf1:10151] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2a94288ff]
[runnervmeorf1:10151] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2a98a5ff5]
[runnervmeorf1:10151] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2a98bb0da]
[runnervmeorf1:10151] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2a98a5a55]
[runnervmeorf1:10151] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2a98a5a6f]
[runnervmeorf1:10151] [ 8] plumed_master(+0x146dd)[0x555e2af346dd]
[runnervmeorf1:10151] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe2a942a1ca]
[runnervmeorf1:10151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe2a942a28b]
[runnervmeorf1:10151] [11] plumed_master(+0x15365)[0x555e2af35365]
[runnervmeorf1:10151] *** End of error message ***
</pre>
{% endraw %}
