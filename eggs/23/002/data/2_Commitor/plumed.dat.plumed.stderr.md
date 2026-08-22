**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervm76f27:07675] *** Process received signal ***
[runnervm76f27:07675] Signal: Aborted (6)
[runnervm76f27:07675] Signal code:  (-6)
[runnervm76f27:07675] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec1ac45330]
[runnervm76f27:07675] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec1ac9ec0c]
[runnervm76f27:07675] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec1ac4527e]
[runnervm76f27:07675] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec1ac288ff]
[runnervm76f27:07675] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec1b0a5ff5]
[runnervm76f27:07675] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec1b0bb0da]
[runnervm76f27:07675] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec1b0a5a55]
[runnervm76f27:07675] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec1b0a5a6f]
[runnervm76f27:07675] [ 8] plumed(+0x146dd)[0x557ccdbb76dd]
[runnervm76f27:07675] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec1ac2a1ca]
[runnervm76f27:07675] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec1ac2a28b]
[runnervm76f27:07675] [11] plumed(+0x15365)[0x557ccdbb8365]
[runnervm76f27:07675] *** End of error message ***
</pre>
{% endraw %}
