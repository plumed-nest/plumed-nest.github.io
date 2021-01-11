**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/128molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f63e42864b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f63e4286428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f63e428802a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f63e48c084d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f63e48be6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f63e48be701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 6] terminate called after throwing an instance of '/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f63e48be919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [10] PLMD::Plumed::ExceptionError/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f63e4271830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07797] *** End of error message ***
'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f99d51cc4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f99d51cc428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f99d51ce02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f99d580684d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f99d58046b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f99d5804701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f99d5804919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f99d51b7830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07798] *** End of error message ***
</pre>
{% endraw %}
