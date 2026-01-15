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
[runnervmi13qx:35466] *** Process received signal ***
[runnervmi13qx:35466] Signal: Aborted (6)
[runnervmi13qx:35466] Signal code:  (-6)
[runnervmi13qx:35466] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcc9845330]
[runnervmi13qx:35466] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcc989eb2c]
[runnervmi13qx:35466] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcc984527e]
[runnervmi13qx:35466] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcc98288ff]
[runnervmi13qx:35466] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcc9ca5ff5]
[runnervmi13qx:35466] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcc9cbb0da]
[runnervmi13qx:35466] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcc9ca5a55]
[runnervmi13qx:35466] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcc9ca5a6f]
[runnervmi13qx:35466] [ 8] plumed_master(+0x146dd)[0x5634696896dd]
[runnervmi13qx:35466] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcc982a1ca]
[runnervmi13qx:35466] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcc982a28b]
[runnervmi13qx:35466] [11] plumed_master(+0x15365)[0x56346968a365]
[runnervmi13qx:35466] *** End of error message ***
</pre>
{% endraw %}
