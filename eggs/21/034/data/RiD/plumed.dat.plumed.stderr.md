**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: DEEPFE LABEL=dpfe TRUST_LVL_1=1.0 TRUST_LVL_2=2.0 MODEL=graph.pb ARG=dih-000-01,dih-001-00,dih-001-01,dih-002-00,dih-002-01,dih-003-00,dih-003-01,dih-004-00,dih-004-01,dih-005-00,dih-005-01,dih-006-00,dih-006-01,dih-007-00,dih-007-01,dih-008-00,dih-008-01,dih-009-00
Maybe a missing space or a typo?
[fv-az695-955:06687] *** Process received signal ***
[fv-az695-955:06687] Signal: Aborted (6)
[fv-az695-955:06687] Signal code:  (-6)
[fv-az695-955:06687] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2f1c442520]
[fv-az695-955:06687] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2f1c4969fc]
[fv-az695-955:06687] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2f1c442476]
[fv-az695-955:06687] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2f1c4287f3]
[fv-az695-955:06687] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2f1c8a2b9e]
[fv-az695-955:06687] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2f1c8ae20c]
[fv-az695-955:06687] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2f1c8ae277]
[fv-az695-955:06687] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2f1c8ae52b]
[fv-az695-955:06687] [ 8] plumed(+0x12f48)[0x5626a1d30f48]
[fv-az695-955:06687] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2f1c429d90]
[fv-az695-955:06687] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2f1c429e40]
[fv-az695-955:06687] [11] plumed(+0x131e5)[0x5626a1d311e5]
[fv-az695-955:06687] *** End of error message ***
</pre>
{% endraw %}
