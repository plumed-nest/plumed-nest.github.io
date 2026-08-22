**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07794] *** Process received signal ***
[runnervm76f27:07794] Signal: Aborted (6)
[runnervm76f27:07794] Signal code:  (-6)
[runnervm76f27:07794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa902845330]
[runnervm76f27:07794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa90289ec0c]
[runnervm76f27:07794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa90284527e]
[runnervm76f27:07794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9028288ff]
[runnervm76f27:07794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa902ca5ff5]
[runnervm76f27:07794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa902cbb0da]
[runnervm76f27:07794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa902ca5a55]
[runnervm76f27:07794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa902ca5a6f]
[runnervm76f27:07794] [ 8] plumed_master(+0x146dd)[0x557842fe16dd]
[runnervm76f27:07794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa90282a1ca]
[runnervm76f27:07794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa90282a28b]
[runnervm76f27:07794] [11] plumed_master(+0x15365)[0x557842fe2365]
[runnervm76f27:07794] *** End of error message ***
</pre>
{% endraw %}
