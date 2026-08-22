**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/1_PIV/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07742] *** Process received signal ***
[runnervm76f27:07742] Signal: Aborted (6)
[runnervm76f27:07742] Signal code:  (-6)
[runnervm76f27:07742] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5f67645330]
[runnervm76f27:07742] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5f6769ec0c]
[runnervm76f27:07742] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5f6764527e]
[runnervm76f27:07742] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5f676288ff]
[runnervm76f27:07742] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5f67aa5ff5]
[runnervm76f27:07742] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5f67abb0da]
[runnervm76f27:07742] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5f67aa5a55]
[runnervm76f27:07742] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5f67aa5a6f]
[runnervm76f27:07742] [ 8] plumed_master(+0x146dd)[0x55b6548626dd]
[runnervm76f27:07742] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5f6762a1ca]
[runnervm76f27:07742] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5f6762a28b]
[runnervm76f27:07742] [11] plumed_master(+0x15365)[0x55b654863365]
[runnervm76f27:07742] *** End of error message ***
</pre>
{% endraw %}
