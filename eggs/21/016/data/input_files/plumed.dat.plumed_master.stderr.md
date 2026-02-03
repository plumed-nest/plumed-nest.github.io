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
[runnervmkj6or:08960] *** Process received signal ***
[runnervmkj6or:08960] Signal: Aborted (6)
[runnervmkj6or:08960] Signal code:  (-6)
[runnervmkj6or:08960] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff875645330]
[runnervmkj6or:08960] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff87569eb2c]
[runnervmkj6or:08960] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff87564527e]
[runnervmkj6or:08960] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8756288ff]
[runnervmkj6or:08960] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff875aa5ff5]
[runnervmkj6or:08960] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff875abb0da]
[runnervmkj6or:08960] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff875aa5a55]
[runnervmkj6or:08960] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff875aa5a6f]
[runnervmkj6or:08960] [ 8] plumed_master(+0x146dd)[0x5625b8b5c6dd]
[runnervmkj6or:08960] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff87562a1ca]
[runnervmkj6or:08960] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff87562a28b]
[runnervmkj6or:08960] [11] plumed_master(+0x15365)[0x5625b8b5d365]
[runnervmkj6or:08960] *** End of error message ***
</pre>
{% endraw %}
