**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[fv-az790-36:65349] *** Process received signal ***
[fv-az790-36:65349] Signal: Aborted (6)
[fv-az790-36:65349] Signal code:  (-6)
[fv-az790-36:65349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f383f645330]
[fv-az790-36:65349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f383f69eb2c]
[fv-az790-36:65349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f383f64527e]
[fv-az790-36:65349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f383f6288ff]
[fv-az790-36:65349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f383faa5ff5]
[fv-az790-36:65349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f383fabb0da]
[fv-az790-36:65349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f383faa5a55]
[fv-az790-36:65349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f383faa5a6f]
[fv-az790-36:65349] [ 8] plumed_master(+0x146dd)[0x55fe3e59c6dd]
[fv-az790-36:65349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f383f62a1ca]
[fv-az790-36:65349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f383f62a28b]
[fv-az790-36:65349] [11] plumed_master(+0x15365)[0x55fe3e59d365]
[fv-az790-36:65349] *** End of error message ***
</pre>
{% endraw %}
