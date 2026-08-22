**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervm76f27:11365] *** Process received signal ***
[runnervm76f27:11365] Signal: Aborted (6)
[runnervm76f27:11365] Signal code:  (-6)
[runnervm76f27:11365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6974a45330]
[runnervm76f27:11365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6974a9ec0c]
[runnervm76f27:11365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6974a4527e]
[runnervm76f27:11365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6974a288ff]
[runnervm76f27:11365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6974ea5ff5]
[runnervm76f27:11365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6974ebb0da]
[runnervm76f27:11365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6974ea5a55]
[runnervm76f27:11365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6974ea5a6f]
[runnervm76f27:11365] [ 8] plumed(+0x146dd)[0x55ad5994c6dd]
[runnervm76f27:11365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6974a2a1ca]
[runnervm76f27:11365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6974a2a28b]
[runnervm76f27:11365] [11] plumed(+0x15365)[0x55ad5994d365]
[runnervm76f27:11365] *** End of error message ***
</pre>
{% endraw %}
