**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[runnervmi13qx:35449] *** Process received signal ***
[runnervmi13qx:35449] Signal: Aborted (6)
[runnervmi13qx:35449] Signal code:  (-6)
[runnervmi13qx:35449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffa26045330]
[runnervmi13qx:35449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffa2609eb2c]
[runnervmi13qx:35449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffa2604527e]
[runnervmi13qx:35449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffa260288ff]
[runnervmi13qx:35449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffa264a5ff5]
[runnervmi13qx:35449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffa264bb0da]
[runnervmi13qx:35449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffa264a5a55]
[runnervmi13qx:35449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffa264a5a6f]
[runnervmi13qx:35449] [ 8] plumed(+0x146dd)[0x5620fbbd06dd]
[runnervmi13qx:35449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffa2602a1ca]
[runnervmi13qx:35449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffa2602a28b]
[runnervmi13qx:35449] [11] plumed(+0x15365)[0x5620fbbd1365]
[runnervmi13qx:35449] *** End of error message ***
</pre>
{% endraw %}
