**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvm7jw40e0xgp:11557] *** Process received signal ***
[pkrvm7jw40e0xgp:11557] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11557] Signal code:  (-6)
[pkrvm7jw40e0xgp:11557] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7f1c45330]
[pkrvm7jw40e0xgp:11557] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7f1c9eb2c]
[pkrvm7jw40e0xgp:11557] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7f1c4527e]
[pkrvm7jw40e0xgp:11557] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7f1c288ff]
[pkrvm7jw40e0xgp:11557] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7f20a5ff5]
[pkrvm7jw40e0xgp:11557] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7f20bb0da]
[pkrvm7jw40e0xgp:11557] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7f20a5a55]
[pkrvm7jw40e0xgp:11557] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7f20a5a6f]
[pkrvm7jw40e0xgp:11557] [ 8] plumed(+0x146dd)[0x558cf4c146dd]
[pkrvm7jw40e0xgp:11557] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7f1c2a1ca]
[pkrvm7jw40e0xgp:11557] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7f1c2a28b]
[pkrvm7jw40e0xgp:11557] [11] plumed(+0x15365)[0x558cf4c15365]
[pkrvm7jw40e0xgp:11557] *** End of error message ***
</pre>
{% endraw %}
