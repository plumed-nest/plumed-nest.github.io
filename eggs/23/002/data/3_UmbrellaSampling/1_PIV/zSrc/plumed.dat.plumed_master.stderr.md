**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmkj6or:06628] *** Process received signal ***
[runnervmkj6or:06628] Signal: Aborted (6)
[runnervmkj6or:06628] Signal code:  (-6)
[runnervmkj6or:06628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48c9245330]
[runnervmkj6or:06628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48c929eb2c]
[runnervmkj6or:06628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48c924527e]
[runnervmkj6or:06628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48c92288ff]
[runnervmkj6or:06628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48c96a5ff5]
[runnervmkj6or:06628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48c96bb0da]
[runnervmkj6or:06628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48c96a5a55]
[runnervmkj6or:06628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48c96a5a6f]
[runnervmkj6or:06628] [ 8] plumed_master(+0x146dd)[0x5610a01d76dd]
[runnervmkj6or:06628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48c922a1ca]
[runnervmkj6or:06628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48c922a28b]
[runnervmkj6or:06628] [11] plumed_master(+0x15365)[0x5610a01d8365]
[runnervmkj6or:06628] *** End of error message ***
</pre>
{% endraw %}
