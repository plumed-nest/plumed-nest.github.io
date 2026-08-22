**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07778] *** Process received signal ***
[runnervm76f27:07778] Signal: Aborted (6)
[runnervm76f27:07778] Signal code:  (-6)
[runnervm76f27:07778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84ad845330]
[runnervm76f27:07778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84ad89ec0c]
[runnervm76f27:07778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84ad84527e]
[runnervm76f27:07778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84ad8288ff]
[runnervm76f27:07778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84adca5ff5]
[runnervm76f27:07778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84adcbb0da]
[runnervm76f27:07778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84adca5a55]
[runnervm76f27:07778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84adca5a6f]
[runnervm76f27:07778] [ 8] plumed(+0x146dd)[0x55c44a0d06dd]
[runnervm76f27:07778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84ad82a1ca]
[runnervm76f27:07778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84ad82a28b]
[runnervm76f27:07778] [11] plumed(+0x15365)[0x55c44a0d1365]
[runnervm76f27:07778] *** End of error message ***
</pre>
{% endraw %}
