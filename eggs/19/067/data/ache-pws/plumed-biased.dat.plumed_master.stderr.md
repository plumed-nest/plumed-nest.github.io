**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvm7jw40e0xgp:11573] *** Process received signal ***
[pkrvm7jw40e0xgp:11573] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11573] Signal code:  (-6)
[pkrvm7jw40e0xgp:11573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efcaea45330]
[pkrvm7jw40e0xgp:11573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efcaea9eb2c]
[pkrvm7jw40e0xgp:11573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efcaea4527e]
[pkrvm7jw40e0xgp:11573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efcaea288ff]
[pkrvm7jw40e0xgp:11573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efcaeea5ff5]
[pkrvm7jw40e0xgp:11573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efcaeebb0da]
[pkrvm7jw40e0xgp:11573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efcaeea5a55]
[pkrvm7jw40e0xgp:11573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efcaeea5a6f]
[pkrvm7jw40e0xgp:11573] [ 8] plumed_master(+0x146dd)[0x55bf393b76dd]
[pkrvm7jw40e0xgp:11573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efcaea2a1ca]
[pkrvm7jw40e0xgp:11573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efcaea2a28b]
[pkrvm7jw40e0xgp:11573] [11] plumed_master(+0x15365)[0x55bf393b8365]
[pkrvm7jw40e0xgp:11573] *** End of error message ***
</pre>
{% endraw %}
