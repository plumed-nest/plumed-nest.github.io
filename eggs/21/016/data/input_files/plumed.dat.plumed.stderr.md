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
[runnervmkj6or:08943] *** Process received signal ***
[runnervmkj6or:08943] Signal: Aborted (6)
[runnervmkj6or:08943] Signal code:  (-6)
[runnervmkj6or:08943] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedf7045330]
[runnervmkj6or:08943] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedf709eb2c]
[runnervmkj6or:08943] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedf704527e]
[runnervmkj6or:08943] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedf70288ff]
[runnervmkj6or:08943] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedf74a5ff5]
[runnervmkj6or:08943] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedf74bb0da]
[runnervmkj6or:08943] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedf74a5a55]
[runnervmkj6or:08943] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedf74a5a6f]
[runnervmkj6or:08943] [ 8] plumed(+0x146dd)[0x55ef23d776dd]
[runnervmkj6or:08943] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedf702a1ca]
[runnervmkj6or:08943] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedf702a28b]
[runnervmkj6or:08943] [11] plumed(+0x15365)[0x55ef23d78365]
[runnervmkj6or:08943] *** End of error message ***
</pre>
{% endraw %}
