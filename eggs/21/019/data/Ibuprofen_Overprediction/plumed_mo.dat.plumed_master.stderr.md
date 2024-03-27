**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: ATOMS285=9378,9382
Maybe a missing space or a typo?
[fv-az1487-606:72603] *** Process received signal ***
[fv-az1487-606:72603] Signal: Aborted (6)
[fv-az1487-606:72603] Signal code:  (-6)
[fv-az1487-606:72603] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff133042520]
[fv-az1487-606:72603] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff1330969fc]
[fv-az1487-606:72603] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff133042476]
[fv-az1487-606:72603] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff1330287f3]
[fv-az1487-606:72603] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7ff1334a4f26]
[fv-az1487-606:72603] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7ff1334b6d9c]
[fv-az1487-606:72603] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7ff1334b6e07]
[fv-az1487-606:72603] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff1334b70bb]
[fv-az1487-606:72603] [ 8] plumed_master(+0x12e7f)[0x556fafbe0e7f]
[fv-az1487-606:72603] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff133029d90]
[fv-az1487-606:72603] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff133029e40]
[fv-az1487-606:72603] [11] plumed_master(+0x13115)[0x556fafbe1115]
[fv-az1487-606:72603] *** End of error message ***
</pre>
{% endraw %}
