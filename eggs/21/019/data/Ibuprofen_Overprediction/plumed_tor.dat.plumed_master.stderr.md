**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: ATOMS141=9314,9319,9310,9313
Maybe a missing space or a typo?
[fv-az1487-606:72634] *** Process received signal ***
[fv-az1487-606:72634] Signal: Aborted (6)
[fv-az1487-606:72634] Signal code:  (-6)
[fv-az1487-606:72634] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fa4e0a42520]
[fv-az1487-606:72634] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fa4e0a969fc]
[fv-az1487-606:72634] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fa4e0a42476]
[fv-az1487-606:72634] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fa4e0a287f3]
[fv-az1487-606:72634] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fa4e0ea4f26]
[fv-az1487-606:72634] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fa4e0eb6d9c]
[fv-az1487-606:72634] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fa4e0eb6e07]
[fv-az1487-606:72634] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fa4e0eb70bb]
[fv-az1487-606:72634] [ 8] plumed_master(+0x12e7f)[0x5649e8e40e7f]
[fv-az1487-606:72634] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fa4e0a29d90]
[fv-az1487-606:72634] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fa4e0a29e40]
[fv-az1487-606:72634] [11] plumed_master(+0x13115)[0x5649e8e41115]
[fv-az1487-606:72634] *** End of error message ***
</pre>
{% endraw %}
