**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[runnervm76f27:04857] *** Process received signal ***
[runnervm76f27:04857] Signal: Aborted (6)
[runnervm76f27:04857] Signal code:  (-6)
[runnervm76f27:04857] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f173fa45330]
[runnervm76f27:04857] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f173fa9ec0c]
[runnervm76f27:04857] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f173fa4527e]
[runnervm76f27:04857] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f173fa288ff]
[runnervm76f27:04857] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f173fea5ff5]
[runnervm76f27:04857] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f173febb0da]
[runnervm76f27:04857] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f173fea5a55]
[runnervm76f27:04857] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f173fea5a6f]
[runnervm76f27:04857] [ 8] plumed(+0x146dd)[0x559f43da86dd]
[runnervm76f27:04857] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f173fa2a1ca]
[runnervm76f27:04857] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f173fa2a28b]
[runnervm76f27:04857] [11] plumed(+0x15365)[0x559f43da9365]
[runnervm76f27:04857] *** End of error message ***
</pre>
{% endraw %}
