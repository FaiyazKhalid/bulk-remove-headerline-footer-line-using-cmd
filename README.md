# bulk-remove-headerline-footer-line-using-cmd

@echo off

set droptop=37
for /f %%i in ( ' find /c /v "" ^<1.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1.html ' ) do if %%i leq %dropend% >>new\1.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<2.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<2.html ' ) do if %%i leq %dropend% >>new\2.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<3.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<3.html ' ) do if %%i leq %dropend% >>new\3.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<4.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<4.html ' ) do if %%i leq %dropend% >>new\4.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<5.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<5.html ' ) do if %%i leq %dropend% >>new\5.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<6.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<6.html ' ) do if %%i leq %dropend% >>new\6.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<7.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<7.html ' ) do if %%i leq %dropend% >>new\7.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<8.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<8.html ' ) do if %%i leq %dropend% >>new\8.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<9.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<9.html ' ) do if %%i leq %dropend% >>new\9.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<10.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<10.html ' ) do if %%i leq %dropend% >>new\10.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<11.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<11.html ' ) do if %%i leq %dropend% >>new\11.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<12.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<12.html ' ) do if %%i leq %dropend% >>new\12.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<13.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<13.html ' ) do if %%i leq %dropend% >>new\13.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<14.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<14.html ' ) do if %%i leq %dropend% >>new\14.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<15.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<15.html ' ) do if %%i leq %dropend% >>new\15.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<16.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<16.html ' ) do if %%i leq %dropend% >>new\16.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<17.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<17.html ' ) do if %%i leq %dropend% >>new\17.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<18.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<18.html ' ) do if %%i leq %dropend% >>new\18.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<19.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<19.html ' ) do if %%i leq %dropend% >>new\19.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<20.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<20.html ' ) do if %%i leq %dropend% >>new\20.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<21.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<21.html ' ) do if %%i leq %dropend% >>new\21.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<22.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<22.html ' ) do if %%i leq %dropend% >>new\22.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<23.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<23.html ' ) do if %%i leq %dropend% >>new\23.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<24.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<24.html ' ) do if %%i leq %dropend% >>new\24.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<25.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<25.html ' ) do if %%i leq %dropend% >>new\25.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<26.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<26.html ' ) do if %%i leq %dropend% >>new\26.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<27.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<27.html ' ) do if %%i leq %dropend% >>new\27.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<28.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<28.html ' ) do if %%i leq %dropend% >>new\28.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<29.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<29.html ' ) do if %%i leq %dropend% >>new\29.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<30.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<30.html ' ) do if %%i leq %dropend% >>new\30.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<31.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<31.html ' ) do if %%i leq %dropend% >>new\31.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<32.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<32.html ' ) do if %%i leq %dropend% >>new\32.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<33.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<33.html ' ) do if %%i leq %dropend% >>new\33.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<34.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<34.html ' ) do if %%i leq %dropend% >>new\34.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<35.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<35.html ' ) do if %%i leq %dropend% >>new\35.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<36.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<36.html ' ) do if %%i leq %dropend% >>new\36.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<37.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<37.html ' ) do if %%i leq %dropend% >>new\37.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<38.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<38.html ' ) do if %%i leq %dropend% >>new\38.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<39.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<39.html ' ) do if %%i leq %dropend% >>new\39.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<40.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<40.html ' ) do if %%i leq %dropend% >>new\40.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<41.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<41.html ' ) do if %%i leq %dropend% >>new\41.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<42.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<42.html ' ) do if %%i leq %dropend% >>new\42.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<43.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<43.html ' ) do if %%i leq %dropend% >>new\43.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<44.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<44.html ' ) do if %%i leq %dropend% >>new\44.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<45.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<45.html ' ) do if %%i leq %dropend% >>new\45.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<46.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<46.html ' ) do if %%i leq %dropend% >>new\46.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<47.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<47.html ' ) do if %%i leq %dropend% >>new\47.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<48.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<48.html ' ) do if %%i leq %dropend% >>new\48.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<49.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<49.html ' ) do if %%i leq %dropend% >>new\49.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<50.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<50.html ' ) do if %%i leq %dropend% >>new\50.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<51.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<51.html ' ) do if %%i leq %dropend% >>new\51.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<52.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<52.html ' ) do if %%i leq %dropend% >>new\52.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<53.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<53.html ' ) do if %%i leq %dropend% >>new\53.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<54.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<54.html ' ) do if %%i leq %dropend% >>new\54.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<55.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<55.html ' ) do if %%i leq %dropend% >>new\55.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<56.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<56.html ' ) do if %%i leq %dropend% >>new\56.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<57.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<57.html ' ) do if %%i leq %dropend% >>new\57.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<58.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<58.html ' ) do if %%i leq %dropend% >>new\58.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<59.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<59.html ' ) do if %%i leq %dropend% >>new\59.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<60.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<60.html ' ) do if %%i leq %dropend% >>new\60.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<61.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<61.html ' ) do if %%i leq %dropend% >>new\61.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<62.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<62.html ' ) do if %%i leq %dropend% >>new\62.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<63.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<63.html ' ) do if %%i leq %dropend% >>new\63.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<64.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<64.html ' ) do if %%i leq %dropend% >>new\64.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<65.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<65.html ' ) do if %%i leq %dropend% >>new\65.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<66.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<66.html ' ) do if %%i leq %dropend% >>new\66.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<67.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<67.html ' ) do if %%i leq %dropend% >>new\67.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<68.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<68.html ' ) do if %%i leq %dropend% >>new\68.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<69.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<69.html ' ) do if %%i leq %dropend% >>new\69.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<70.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<70.html ' ) do if %%i leq %dropend% >>new\70.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<71.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<71.html ' ) do if %%i leq %dropend% >>new\71.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<72.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<72.html ' ) do if %%i leq %dropend% >>new\72.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<73.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<73.html ' ) do if %%i leq %dropend% >>new\73.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<74.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<74.html ' ) do if %%i leq %dropend% >>new\74.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<75.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<75.html ' ) do if %%i leq %dropend% >>new\75.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<76.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<76.html ' ) do if %%i leq %dropend% >>new\76.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<77.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<77.html ' ) do if %%i leq %dropend% >>new\77.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<78.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<78.html ' ) do if %%i leq %dropend% >>new\78.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<79.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<79.html ' ) do if %%i leq %dropend% >>new\79.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<80.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<80.html ' ) do if %%i leq %dropend% >>new\80.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<81.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<81.html ' ) do if %%i leq %dropend% >>new\81.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<82.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<82.html ' ) do if %%i leq %dropend% >>new\82.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<83.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<83.html ' ) do if %%i leq %dropend% >>new\83.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<84.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<84.html ' ) do if %%i leq %dropend% >>new\84.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<85.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<85.html ' ) do if %%i leq %dropend% >>new\85.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<86.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<86.html ' ) do if %%i leq %dropend% >>new\86.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<87.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<87.html ' ) do if %%i leq %dropend% >>new\87.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<88.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<88.html ' ) do if %%i leq %dropend% >>new\88.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<89.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<89.html ' ) do if %%i leq %dropend% >>new\89.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<90.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<90.html ' ) do if %%i leq %dropend% >>new\90.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<91.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<91.html ' ) do if %%i leq %dropend% >>new\91.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<92.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<92.html ' ) do if %%i leq %dropend% >>new\92.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<93.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<93.html ' ) do if %%i leq %dropend% >>new\93.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<94.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<94.html ' ) do if %%i leq %dropend% >>new\94.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<95.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<95.html ' ) do if %%i leq %dropend% >>new\95.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<96.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<96.html ' ) do if %%i leq %dropend% >>new\96.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<97.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<97.html ' ) do if %%i leq %dropend% >>new\97.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<98.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<98.html ' ) do if %%i leq %dropend% >>new\98.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<99.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<99.html ' ) do if %%i leq %dropend% >>new\99.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<100.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<100.html ' ) do if %%i leq %dropend% >>new\100.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<101.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<101.html ' ) do if %%i leq %dropend% >>new\101.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<102.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<102.html ' ) do if %%i leq %dropend% >>new\102.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<103.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<103.html ' ) do if %%i leq %dropend% >>new\103.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<104.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<104.html ' ) do if %%i leq %dropend% >>new\104.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<105.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<105.html ' ) do if %%i leq %dropend% >>new\105.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<106.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<106.html ' ) do if %%i leq %dropend% >>new\106.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<107.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<107.html ' ) do if %%i leq %dropend% >>new\107.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<108.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<108.html ' ) do if %%i leq %dropend% >>new\108.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<109.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<109.html ' ) do if %%i leq %dropend% >>new\109.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<110.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<110.html ' ) do if %%i leq %dropend% >>new\110.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<111.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<111.html ' ) do if %%i leq %dropend% >>new\111.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<112.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<112.html ' ) do if %%i leq %dropend% >>new\112.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<113.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<113.html ' ) do if %%i leq %dropend% >>new\113.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<114.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<114.html ' ) do if %%i leq %dropend% >>new\114.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<115.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<115.html ' ) do if %%i leq %dropend% >>new\115.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<116.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<116.html ' ) do if %%i leq %dropend% >>new\116.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<117.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<117.html ' ) do if %%i leq %dropend% >>new\117.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<118.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<118.html ' ) do if %%i leq %dropend% >>new\118.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<119.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<119.html ' ) do if %%i leq %dropend% >>new\119.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<120.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<120.html ' ) do if %%i leq %dropend% >>new\120.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<121.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<121.html ' ) do if %%i leq %dropend% >>new\121.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<122.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<122.html ' ) do if %%i leq %dropend% >>new\122.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<123.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<123.html ' ) do if %%i leq %dropend% >>new\123.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<124.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<124.html ' ) do if %%i leq %dropend% >>new\124.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<125.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<125.html ' ) do if %%i leq %dropend% >>new\125.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<126.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<126.html ' ) do if %%i leq %dropend% >>new\126.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<127.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<127.html ' ) do if %%i leq %dropend% >>new\127.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<128.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<128.html ' ) do if %%i leq %dropend% >>new\128.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<129.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<129.html ' ) do if %%i leq %dropend% >>new\129.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<130.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<130.html ' ) do if %%i leq %dropend% >>new\130.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<131.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<131.html ' ) do if %%i leq %dropend% >>new\131.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<132.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<132.html ' ) do if %%i leq %dropend% >>new\132.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<133.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<133.html ' ) do if %%i leq %dropend% >>new\133.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<134.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<134.html ' ) do if %%i leq %dropend% >>new\134.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<135.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<135.html ' ) do if %%i leq %dropend% >>new\135.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<136.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<136.html ' ) do if %%i leq %dropend% >>new\136.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<137.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<137.html ' ) do if %%i leq %dropend% >>new\137.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<138.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<138.html ' ) do if %%i leq %dropend% >>new\138.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<139.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<139.html ' ) do if %%i leq %dropend% >>new\139.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<140.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<140.html ' ) do if %%i leq %dropend% >>new\140.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<141.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<141.html ' ) do if %%i leq %dropend% >>new\141.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<142.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<142.html ' ) do if %%i leq %dropend% >>new\142.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<143.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<143.html ' ) do if %%i leq %dropend% >>new\143.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<144.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<144.html ' ) do if %%i leq %dropend% >>new\144.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<145.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<145.html ' ) do if %%i leq %dropend% >>new\145.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<146.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<146.html ' ) do if %%i leq %dropend% >>new\146.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<147.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<147.html ' ) do if %%i leq %dropend% >>new\147.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<148.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<148.html ' ) do if %%i leq %dropend% >>new\148.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<149.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<149.html ' ) do if %%i leq %dropend% >>new\149.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<150.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<150.html ' ) do if %%i leq %dropend% >>new\150.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<151.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<151.html ' ) do if %%i leq %dropend% >>new\151.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<152.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<152.html ' ) do if %%i leq %dropend% >>new\152.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<153.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<153.html ' ) do if %%i leq %dropend% >>new\153.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<154.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<154.html ' ) do if %%i leq %dropend% >>new\154.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<155.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<155.html ' ) do if %%i leq %dropend% >>new\155.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<156.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<156.html ' ) do if %%i leq %dropend% >>new\156.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<157.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<157.html ' ) do if %%i leq %dropend% >>new\157.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<158.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<158.html ' ) do if %%i leq %dropend% >>new\158.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<159.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<159.html ' ) do if %%i leq %dropend% >>new\159.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<160.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<160.html ' ) do if %%i leq %dropend% >>new\160.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<161.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<161.html ' ) do if %%i leq %dropend% >>new\161.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<162.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<162.html ' ) do if %%i leq %dropend% >>new\162.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<163.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<163.html ' ) do if %%i leq %dropend% >>new\163.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<164.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<164.html ' ) do if %%i leq %dropend% >>new\164.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<165.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<165.html ' ) do if %%i leq %dropend% >>new\165.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<166.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<166.html ' ) do if %%i leq %dropend% >>new\166.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<167.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<167.html ' ) do if %%i leq %dropend% >>new\167.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<168.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<168.html ' ) do if %%i leq %dropend% >>new\168.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<169.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<169.html ' ) do if %%i leq %dropend% >>new\169.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<170.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<170.html ' ) do if %%i leq %dropend% >>new\170.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<171.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<171.html ' ) do if %%i leq %dropend% >>new\171.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<172.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<172.html ' ) do if %%i leq %dropend% >>new\172.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<173.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<173.html ' ) do if %%i leq %dropend% >>new\173.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<174.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<174.html ' ) do if %%i leq %dropend% >>new\174.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<175.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<175.html ' ) do if %%i leq %dropend% >>new\175.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<176.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<176.html ' ) do if %%i leq %dropend% >>new\176.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<177.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<177.html ' ) do if %%i leq %dropend% >>new\177.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<178.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<178.html ' ) do if %%i leq %dropend% >>new\178.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<179.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<179.html ' ) do if %%i leq %dropend% >>new\179.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<180.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<180.html ' ) do if %%i leq %dropend% >>new\180.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<181.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<181.html ' ) do if %%i leq %dropend% >>new\181.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<182.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<182.html ' ) do if %%i leq %dropend% >>new\182.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<183.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<183.html ' ) do if %%i leq %dropend% >>new\183.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<184.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<184.html ' ) do if %%i leq %dropend% >>new\184.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<185.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<185.html ' ) do if %%i leq %dropend% >>new\185.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<186.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<186.html ' ) do if %%i leq %dropend% >>new\186.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<187.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<187.html ' ) do if %%i leq %dropend% >>new\187.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<188.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<188.html ' ) do if %%i leq %dropend% >>new\188.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<189.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<189.html ' ) do if %%i leq %dropend% >>new\189.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<190.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<190.html ' ) do if %%i leq %dropend% >>new\190.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<191.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<191.html ' ) do if %%i leq %dropend% >>new\191.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<192.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<192.html ' ) do if %%i leq %dropend% >>new\192.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<193.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<193.html ' ) do if %%i leq %dropend% >>new\193.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<194.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<194.html ' ) do if %%i leq %dropend% >>new\194.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<195.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<195.html ' ) do if %%i leq %dropend% >>new\195.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<196.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<196.html ' ) do if %%i leq %dropend% >>new\196.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<197.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<197.html ' ) do if %%i leq %dropend% >>new\197.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<198.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<198.html ' ) do if %%i leq %dropend% >>new\198.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<199.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<199.html ' ) do if %%i leq %dropend% >>new\199.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<200.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<200.html ' ) do if %%i leq %dropend% >>new\200.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<201.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<201.html ' ) do if %%i leq %dropend% >>new\201.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<202.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<202.html ' ) do if %%i leq %dropend% >>new\202.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<203.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<203.html ' ) do if %%i leq %dropend% >>new\203.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<204.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<204.html ' ) do if %%i leq %dropend% >>new\204.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<205.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<205.html ' ) do if %%i leq %dropend% >>new\205.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<206.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<206.html ' ) do if %%i leq %dropend% >>new\206.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<207.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<207.html ' ) do if %%i leq %dropend% >>new\207.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<208.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<208.html ' ) do if %%i leq %dropend% >>new\208.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<209.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<209.html ' ) do if %%i leq %dropend% >>new\209.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<210.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<210.html ' ) do if %%i leq %dropend% >>new\210.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<211.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<211.html ' ) do if %%i leq %dropend% >>new\211.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<212.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<212.html ' ) do if %%i leq %dropend% >>new\212.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<213.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<213.html ' ) do if %%i leq %dropend% >>new\213.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<214.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<214.html ' ) do if %%i leq %dropend% >>new\214.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<215.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<215.html ' ) do if %%i leq %dropend% >>new\215.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<216.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<216.html ' ) do if %%i leq %dropend% >>new\216.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<217.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<217.html ' ) do if %%i leq %dropend% >>new\217.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<218.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<218.html ' ) do if %%i leq %dropend% >>new\218.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<219.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<219.html ' ) do if %%i leq %dropend% >>new\219.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<220.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<220.html ' ) do if %%i leq %dropend% >>new\220.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<221.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<221.html ' ) do if %%i leq %dropend% >>new\221.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<222.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<222.html ' ) do if %%i leq %dropend% >>new\222.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<223.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<223.html ' ) do if %%i leq %dropend% >>new\223.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<224.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<224.html ' ) do if %%i leq %dropend% >>new\224.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<225.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<225.html ' ) do if %%i leq %dropend% >>new\225.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<226.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<226.html ' ) do if %%i leq %dropend% >>new\226.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<227.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<227.html ' ) do if %%i leq %dropend% >>new\227.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<228.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<228.html ' ) do if %%i leq %dropend% >>new\228.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<229.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<229.html ' ) do if %%i leq %dropend% >>new\229.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<230.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<230.html ' ) do if %%i leq %dropend% >>new\230.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<231.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<231.html ' ) do if %%i leq %dropend% >>new\231.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<232.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<232.html ' ) do if %%i leq %dropend% >>new\232.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<233.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<233.html ' ) do if %%i leq %dropend% >>new\233.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<234.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<234.html ' ) do if %%i leq %dropend% >>new\234.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<235.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<235.html ' ) do if %%i leq %dropend% >>new\235.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<236.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<236.html ' ) do if %%i leq %dropend% >>new\236.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<237.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<237.html ' ) do if %%i leq %dropend% >>new\237.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<238.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<238.html ' ) do if %%i leq %dropend% >>new\238.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<239.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<239.html ' ) do if %%i leq %dropend% >>new\239.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<240.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<240.html ' ) do if %%i leq %dropend% >>new\240.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<241.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<241.html ' ) do if %%i leq %dropend% >>new\241.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<242.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<242.html ' ) do if %%i leq %dropend% >>new\242.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<243.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<243.html ' ) do if %%i leq %dropend% >>new\243.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<244.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<244.html ' ) do if %%i leq %dropend% >>new\244.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<245.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<245.html ' ) do if %%i leq %dropend% >>new\245.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<246.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<246.html ' ) do if %%i leq %dropend% >>new\246.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<247.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<247.html ' ) do if %%i leq %dropend% >>new\247.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<248.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<248.html ' ) do if %%i leq %dropend% >>new\248.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<249.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<249.html ' ) do if %%i leq %dropend% >>new\249.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<250.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<250.html ' ) do if %%i leq %dropend% >>new\250.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<251.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<251.html ' ) do if %%i leq %dropend% >>new\251.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<252.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<252.html ' ) do if %%i leq %dropend% >>new\252.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<253.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<253.html ' ) do if %%i leq %dropend% >>new\253.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<254.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<254.html ' ) do if %%i leq %dropend% >>new\254.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<255.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<255.html ' ) do if %%i leq %dropend% >>new\255.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<256.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<256.html ' ) do if %%i leq %dropend% >>new\256.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<257.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<257.html ' ) do if %%i leq %dropend% >>new\257.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<258.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<258.html ' ) do if %%i leq %dropend% >>new\258.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<259.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<259.html ' ) do if %%i leq %dropend% >>new\259.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<260.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<260.html ' ) do if %%i leq %dropend% >>new\260.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<261.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<261.html ' ) do if %%i leq %dropend% >>new\261.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<262.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<262.html ' ) do if %%i leq %dropend% >>new\262.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<263.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<263.html ' ) do if %%i leq %dropend% >>new\263.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<264.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<264.html ' ) do if %%i leq %dropend% >>new\264.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<265.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<265.html ' ) do if %%i leq %dropend% >>new\265.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<266.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<266.html ' ) do if %%i leq %dropend% >>new\266.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<267.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<267.html ' ) do if %%i leq %dropend% >>new\267.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<268.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<268.html ' ) do if %%i leq %dropend% >>new\268.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<269.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<269.html ' ) do if %%i leq %dropend% >>new\269.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<270.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<270.html ' ) do if %%i leq %dropend% >>new\270.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<271.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<271.html ' ) do if %%i leq %dropend% >>new\271.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<272.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<272.html ' ) do if %%i leq %dropend% >>new\272.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<273.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<273.html ' ) do if %%i leq %dropend% >>new\273.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<274.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<274.html ' ) do if %%i leq %dropend% >>new\274.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<275.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<275.html ' ) do if %%i leq %dropend% >>new\275.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<276.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<276.html ' ) do if %%i leq %dropend% >>new\276.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<277.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<277.html ' ) do if %%i leq %dropend% >>new\277.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<278.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<278.html ' ) do if %%i leq %dropend% >>new\278.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<279.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<279.html ' ) do if %%i leq %dropend% >>new\279.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<280.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<280.html ' ) do if %%i leq %dropend% >>new\280.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<281.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<281.html ' ) do if %%i leq %dropend% >>new\281.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<282.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<282.html ' ) do if %%i leq %dropend% >>new\282.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<283.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<283.html ' ) do if %%i leq %dropend% >>new\283.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<284.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<284.html ' ) do if %%i leq %dropend% >>new\284.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<285.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<285.html ' ) do if %%i leq %dropend% >>new\285.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<286.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<286.html ' ) do if %%i leq %dropend% >>new\286.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<287.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<287.html ' ) do if %%i leq %dropend% >>new\287.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<288.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<288.html ' ) do if %%i leq %dropend% >>new\288.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<289.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<289.html ' ) do if %%i leq %dropend% >>new\289.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<290.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<290.html ' ) do if %%i leq %dropend% >>new\290.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<291.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<291.html ' ) do if %%i leq %dropend% >>new\291.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<292.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<292.html ' ) do if %%i leq %dropend% >>new\292.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<293.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<293.html ' ) do if %%i leq %dropend% >>new\293.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<294.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<294.html ' ) do if %%i leq %dropend% >>new\294.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<295.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<295.html ' ) do if %%i leq %dropend% >>new\295.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<296.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<296.html ' ) do if %%i leq %dropend% >>new\296.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<297.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<297.html ' ) do if %%i leq %dropend% >>new\297.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<298.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<298.html ' ) do if %%i leq %dropend% >>new\298.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<299.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<299.html ' ) do if %%i leq %dropend% >>new\299.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<300.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<300.html ' ) do if %%i leq %dropend% >>new\300.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<301.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<301.html ' ) do if %%i leq %dropend% >>new\301.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<302.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<302.html ' ) do if %%i leq %dropend% >>new\302.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<303.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<303.html ' ) do if %%i leq %dropend% >>new\303.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<304.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<304.html ' ) do if %%i leq %dropend% >>new\304.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<305.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<305.html ' ) do if %%i leq %dropend% >>new\305.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<306.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<306.html ' ) do if %%i leq %dropend% >>new\306.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<307.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<307.html ' ) do if %%i leq %dropend% >>new\307.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<308.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<308.html ' ) do if %%i leq %dropend% >>new\308.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<309.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<309.html ' ) do if %%i leq %dropend% >>new\309.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<310.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<310.html ' ) do if %%i leq %dropend% >>new\310.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<311.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<311.html ' ) do if %%i leq %dropend% >>new\311.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<312.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<312.html ' ) do if %%i leq %dropend% >>new\312.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<313.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<313.html ' ) do if %%i leq %dropend% >>new\313.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<314.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<314.html ' ) do if %%i leq %dropend% >>new\314.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<315.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<315.html ' ) do if %%i leq %dropend% >>new\315.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<316.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<316.html ' ) do if %%i leq %dropend% >>new\316.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<317.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<317.html ' ) do if %%i leq %dropend% >>new\317.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<318.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<318.html ' ) do if %%i leq %dropend% >>new\318.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<319.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<319.html ' ) do if %%i leq %dropend% >>new\319.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<320.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<320.html ' ) do if %%i leq %dropend% >>new\320.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<321.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<321.html ' ) do if %%i leq %dropend% >>new\321.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<322.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<322.html ' ) do if %%i leq %dropend% >>new\322.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<323.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<323.html ' ) do if %%i leq %dropend% >>new\323.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<324.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<324.html ' ) do if %%i leq %dropend% >>new\324.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<325.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<325.html ' ) do if %%i leq %dropend% >>new\325.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<326.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<326.html ' ) do if %%i leq %dropend% >>new\326.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<327.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<327.html ' ) do if %%i leq %dropend% >>new\327.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<328.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<328.html ' ) do if %%i leq %dropend% >>new\328.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<329.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<329.html ' ) do if %%i leq %dropend% >>new\329.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<330.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<330.html ' ) do if %%i leq %dropend% >>new\330.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<331.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<331.html ' ) do if %%i leq %dropend% >>new\331.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<332.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<332.html ' ) do if %%i leq %dropend% >>new\332.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<333.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<333.html ' ) do if %%i leq %dropend% >>new\333.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<334.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<334.html ' ) do if %%i leq %dropend% >>new\334.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<335.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<335.html ' ) do if %%i leq %dropend% >>new\335.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<336.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<336.html ' ) do if %%i leq %dropend% >>new\336.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<337.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<337.html ' ) do if %%i leq %dropend% >>new\337.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<338.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<338.html ' ) do if %%i leq %dropend% >>new\338.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<339.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<339.html ' ) do if %%i leq %dropend% >>new\339.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<340.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<340.html ' ) do if %%i leq %dropend% >>new\340.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<341.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<341.html ' ) do if %%i leq %dropend% >>new\341.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<342.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<342.html ' ) do if %%i leq %dropend% >>new\342.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<343.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<343.html ' ) do if %%i leq %dropend% >>new\343.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<344.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<344.html ' ) do if %%i leq %dropend% >>new\344.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<345.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<345.html ' ) do if %%i leq %dropend% >>new\345.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<346.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<346.html ' ) do if %%i leq %dropend% >>new\346.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<347.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<347.html ' ) do if %%i leq %dropend% >>new\347.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<348.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<348.html ' ) do if %%i leq %dropend% >>new\348.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<349.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<349.html ' ) do if %%i leq %dropend% >>new\349.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<350.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<350.html ' ) do if %%i leq %dropend% >>new\350.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<351.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<351.html ' ) do if %%i leq %dropend% >>new\351.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<352.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<352.html ' ) do if %%i leq %dropend% >>new\352.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<353.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<353.html ' ) do if %%i leq %dropend% >>new\353.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<354.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<354.html ' ) do if %%i leq %dropend% >>new\354.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<355.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<355.html ' ) do if %%i leq %dropend% >>new\355.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<356.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<356.html ' ) do if %%i leq %dropend% >>new\356.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<357.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<357.html ' ) do if %%i leq %dropend% >>new\357.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<358.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<358.html ' ) do if %%i leq %dropend% >>new\358.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<359.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<359.html ' ) do if %%i leq %dropend% >>new\359.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<360.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<360.html ' ) do if %%i leq %dropend% >>new\360.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<361.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<361.html ' ) do if %%i leq %dropend% >>new\361.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<362.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<362.html ' ) do if %%i leq %dropend% >>new\362.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<363.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<363.html ' ) do if %%i leq %dropend% >>new\363.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<364.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<364.html ' ) do if %%i leq %dropend% >>new\364.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<365.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<365.html ' ) do if %%i leq %dropend% >>new\365.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<366.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<366.html ' ) do if %%i leq %dropend% >>new\366.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<367.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<367.html ' ) do if %%i leq %dropend% >>new\367.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<368.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<368.html ' ) do if %%i leq %dropend% >>new\368.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<369.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<369.html ' ) do if %%i leq %dropend% >>new\369.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<370.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<370.html ' ) do if %%i leq %dropend% >>new\370.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<371.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<371.html ' ) do if %%i leq %dropend% >>new\371.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<372.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<372.html ' ) do if %%i leq %dropend% >>new\372.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<373.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<373.html ' ) do if %%i leq %dropend% >>new\373.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<374.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<374.html ' ) do if %%i leq %dropend% >>new\374.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<375.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<375.html ' ) do if %%i leq %dropend% >>new\375.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<376.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<376.html ' ) do if %%i leq %dropend% >>new\376.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<377.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<377.html ' ) do if %%i leq %dropend% >>new\377.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<378.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<378.html ' ) do if %%i leq %dropend% >>new\378.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<379.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<379.html ' ) do if %%i leq %dropend% >>new\379.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<380.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<380.html ' ) do if %%i leq %dropend% >>new\380.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<381.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<381.html ' ) do if %%i leq %dropend% >>new\381.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<382.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<382.html ' ) do if %%i leq %dropend% >>new\382.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<383.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<383.html ' ) do if %%i leq %dropend% >>new\383.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<384.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<384.html ' ) do if %%i leq %dropend% >>new\384.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<385.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<385.html ' ) do if %%i leq %dropend% >>new\385.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<386.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<386.html ' ) do if %%i leq %dropend% >>new\386.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<387.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<387.html ' ) do if %%i leq %dropend% >>new\387.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<388.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<388.html ' ) do if %%i leq %dropend% >>new\388.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<389.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<389.html ' ) do if %%i leq %dropend% >>new\389.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<390.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<390.html ' ) do if %%i leq %dropend% >>new\390.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<391.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<391.html ' ) do if %%i leq %dropend% >>new\391.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<392.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<392.html ' ) do if %%i leq %dropend% >>new\392.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<393.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<393.html ' ) do if %%i leq %dropend% >>new\393.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<394.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<394.html ' ) do if %%i leq %dropend% >>new\394.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<395.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<395.html ' ) do if %%i leq %dropend% >>new\395.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<396.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<396.html ' ) do if %%i leq %dropend% >>new\396.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<397.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<397.html ' ) do if %%i leq %dropend% >>new\397.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<398.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<398.html ' ) do if %%i leq %dropend% >>new\398.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<399.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<399.html ' ) do if %%i leq %dropend% >>new\399.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<400.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<400.html ' ) do if %%i leq %dropend% >>new\400.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<401.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<401.html ' ) do if %%i leq %dropend% >>new\401.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<402.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<402.html ' ) do if %%i leq %dropend% >>new\402.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<403.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<403.html ' ) do if %%i leq %dropend% >>new\403.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<404.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<404.html ' ) do if %%i leq %dropend% >>new\404.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<405.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<405.html ' ) do if %%i leq %dropend% >>new\405.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<406.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<406.html ' ) do if %%i leq %dropend% >>new\406.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<407.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<407.html ' ) do if %%i leq %dropend% >>new\407.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<408.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<408.html ' ) do if %%i leq %dropend% >>new\408.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<409.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<409.html ' ) do if %%i leq %dropend% >>new\409.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<410.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<410.html ' ) do if %%i leq %dropend% >>new\410.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<411.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<411.html ' ) do if %%i leq %dropend% >>new\411.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<412.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<412.html ' ) do if %%i leq %dropend% >>new\412.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<413.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<413.html ' ) do if %%i leq %dropend% >>new\413.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<414.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<414.html ' ) do if %%i leq %dropend% >>new\414.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<415.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<415.html ' ) do if %%i leq %dropend% >>new\415.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<416.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<416.html ' ) do if %%i leq %dropend% >>new\416.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<417.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<417.html ' ) do if %%i leq %dropend% >>new\417.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<418.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<418.html ' ) do if %%i leq %dropend% >>new\418.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<419.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<419.html ' ) do if %%i leq %dropend% >>new\419.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<420.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<420.html ' ) do if %%i leq %dropend% >>new\420.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<421.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<421.html ' ) do if %%i leq %dropend% >>new\421.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<422.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<422.html ' ) do if %%i leq %dropend% >>new\422.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<423.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<423.html ' ) do if %%i leq %dropend% >>new\423.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<424.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<424.html ' ) do if %%i leq %dropend% >>new\424.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<425.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<425.html ' ) do if %%i leq %dropend% >>new\425.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<426.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<426.html ' ) do if %%i leq %dropend% >>new\426.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<427.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<427.html ' ) do if %%i leq %dropend% >>new\427.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<428.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<428.html ' ) do if %%i leq %dropend% >>new\428.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<429.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<429.html ' ) do if %%i leq %dropend% >>new\429.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<430.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<430.html ' ) do if %%i leq %dropend% >>new\430.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<431.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<431.html ' ) do if %%i leq %dropend% >>new\431.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<432.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<432.html ' ) do if %%i leq %dropend% >>new\432.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<433.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<433.html ' ) do if %%i leq %dropend% >>new\433.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<434.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<434.html ' ) do if %%i leq %dropend% >>new\434.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<435.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<435.html ' ) do if %%i leq %dropend% >>new\435.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<436.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<436.html ' ) do if %%i leq %dropend% >>new\436.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<437.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<437.html ' ) do if %%i leq %dropend% >>new\437.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<438.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<438.html ' ) do if %%i leq %dropend% >>new\438.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<439.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<439.html ' ) do if %%i leq %dropend% >>new\439.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<440.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<440.html ' ) do if %%i leq %dropend% >>new\440.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<441.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<441.html ' ) do if %%i leq %dropend% >>new\441.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<442.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<442.html ' ) do if %%i leq %dropend% >>new\442.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<443.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<443.html ' ) do if %%i leq %dropend% >>new\443.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<444.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<444.html ' ) do if %%i leq %dropend% >>new\444.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<445.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<445.html ' ) do if %%i leq %dropend% >>new\445.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<446.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<446.html ' ) do if %%i leq %dropend% >>new\446.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<447.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<447.html ' ) do if %%i leq %dropend% >>new\447.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<448.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<448.html ' ) do if %%i leq %dropend% >>new\448.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<449.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<449.html ' ) do if %%i leq %dropend% >>new\449.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<450.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<450.html ' ) do if %%i leq %dropend% >>new\450.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<451.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<451.html ' ) do if %%i leq %dropend% >>new\451.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<452.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<452.html ' ) do if %%i leq %dropend% >>new\452.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<453.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<453.html ' ) do if %%i leq %dropend% >>new\453.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<454.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<454.html ' ) do if %%i leq %dropend% >>new\454.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<455.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<455.html ' ) do if %%i leq %dropend% >>new\455.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<456.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<456.html ' ) do if %%i leq %dropend% >>new\456.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<457.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<457.html ' ) do if %%i leq %dropend% >>new\457.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<458.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<458.html ' ) do if %%i leq %dropend% >>new\458.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<459.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<459.html ' ) do if %%i leq %dropend% >>new\459.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<460.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<460.html ' ) do if %%i leq %dropend% >>new\460.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<461.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<461.html ' ) do if %%i leq %dropend% >>new\461.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<462.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<462.html ' ) do if %%i leq %dropend% >>new\462.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<463.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<463.html ' ) do if %%i leq %dropend% >>new\463.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<464.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<464.html ' ) do if %%i leq %dropend% >>new\464.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<465.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<465.html ' ) do if %%i leq %dropend% >>new\465.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<466.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<466.html ' ) do if %%i leq %dropend% >>new\466.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<467.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<467.html ' ) do if %%i leq %dropend% >>new\467.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<468.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<468.html ' ) do if %%i leq %dropend% >>new\468.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<469.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<469.html ' ) do if %%i leq %dropend% >>new\469.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<470.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<470.html ' ) do if %%i leq %dropend% >>new\470.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<471.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<471.html ' ) do if %%i leq %dropend% >>new\471.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<472.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<472.html ' ) do if %%i leq %dropend% >>new\472.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<473.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<473.html ' ) do if %%i leq %dropend% >>new\473.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<474.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<474.html ' ) do if %%i leq %dropend% >>new\474.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<475.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<475.html ' ) do if %%i leq %dropend% >>new\475.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<476.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<476.html ' ) do if %%i leq %dropend% >>new\476.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<477.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<477.html ' ) do if %%i leq %dropend% >>new\477.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<478.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<478.html ' ) do if %%i leq %dropend% >>new\478.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<479.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<479.html ' ) do if %%i leq %dropend% >>new\479.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<480.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<480.html ' ) do if %%i leq %dropend% >>new\480.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<481.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<481.html ' ) do if %%i leq %dropend% >>new\481.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<482.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<482.html ' ) do if %%i leq %dropend% >>new\482.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<483.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<483.html ' ) do if %%i leq %dropend% >>new\483.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<484.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<484.html ' ) do if %%i leq %dropend% >>new\484.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<485.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<485.html ' ) do if %%i leq %dropend% >>new\485.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<486.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<486.html ' ) do if %%i leq %dropend% >>new\486.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<487.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<487.html ' ) do if %%i leq %dropend% >>new\487.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<488.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<488.html ' ) do if %%i leq %dropend% >>new\488.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<489.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<489.html ' ) do if %%i leq %dropend% >>new\489.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<490.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<490.html ' ) do if %%i leq %dropend% >>new\490.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<491.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<491.html ' ) do if %%i leq %dropend% >>new\491.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<492.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<492.html ' ) do if %%i leq %dropend% >>new\492.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<493.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<493.html ' ) do if %%i leq %dropend% >>new\493.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<494.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<494.html ' ) do if %%i leq %dropend% >>new\494.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<495.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<495.html ' ) do if %%i leq %dropend% >>new\495.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<496.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<496.html ' ) do if %%i leq %dropend% >>new\496.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<497.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<497.html ' ) do if %%i leq %dropend% >>new\497.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<498.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<498.html ' ) do if %%i leq %dropend% >>new\498.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<499.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<499.html ' ) do if %%i leq %dropend% >>new\499.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<500.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<500.html ' ) do if %%i leq %dropend% >>new\500.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<501.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<501.html ' ) do if %%i leq %dropend% >>new\501.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<502.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<502.html ' ) do if %%i leq %dropend% >>new\502.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<503.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<503.html ' ) do if %%i leq %dropend% >>new\503.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<504.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<504.html ' ) do if %%i leq %dropend% >>new\504.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<505.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<505.html ' ) do if %%i leq %dropend% >>new\505.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<506.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<506.html ' ) do if %%i leq %dropend% >>new\506.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<507.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<507.html ' ) do if %%i leq %dropend% >>new\507.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<508.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<508.html ' ) do if %%i leq %dropend% >>new\508.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<509.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<509.html ' ) do if %%i leq %dropend% >>new\509.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<510.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<510.html ' ) do if %%i leq %dropend% >>new\510.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<511.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<511.html ' ) do if %%i leq %dropend% >>new\511.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<512.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<512.html ' ) do if %%i leq %dropend% >>new\512.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<513.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<513.html ' ) do if %%i leq %dropend% >>new\513.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<514.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<514.html ' ) do if %%i leq %dropend% >>new\514.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<515.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<515.html ' ) do if %%i leq %dropend% >>new\515.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<516.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<516.html ' ) do if %%i leq %dropend% >>new\516.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<517.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<517.html ' ) do if %%i leq %dropend% >>new\517.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<518.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<518.html ' ) do if %%i leq %dropend% >>new\518.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<519.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<519.html ' ) do if %%i leq %dropend% >>new\519.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<520.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<520.html ' ) do if %%i leq %dropend% >>new\520.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<521.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<521.html ' ) do if %%i leq %dropend% >>new\521.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<522.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<522.html ' ) do if %%i leq %dropend% >>new\522.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<523.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<523.html ' ) do if %%i leq %dropend% >>new\523.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<524.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<524.html ' ) do if %%i leq %dropend% >>new\524.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<525.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<525.html ' ) do if %%i leq %dropend% >>new\525.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<526.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<526.html ' ) do if %%i leq %dropend% >>new\526.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<527.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<527.html ' ) do if %%i leq %dropend% >>new\527.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<528.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<528.html ' ) do if %%i leq %dropend% >>new\528.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<529.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<529.html ' ) do if %%i leq %dropend% >>new\529.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<530.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<530.html ' ) do if %%i leq %dropend% >>new\530.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<531.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<531.html ' ) do if %%i leq %dropend% >>new\531.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<532.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<532.html ' ) do if %%i leq %dropend% >>new\532.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<533.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<533.html ' ) do if %%i leq %dropend% >>new\533.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<534.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<534.html ' ) do if %%i leq %dropend% >>new\534.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<535.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<535.html ' ) do if %%i leq %dropend% >>new\535.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<536.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<536.html ' ) do if %%i leq %dropend% >>new\536.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<537.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<537.html ' ) do if %%i leq %dropend% >>new\537.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<538.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<538.html ' ) do if %%i leq %dropend% >>new\538.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<539.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<539.html ' ) do if %%i leq %dropend% >>new\539.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<540.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<540.html ' ) do if %%i leq %dropend% >>new\540.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<541.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<541.html ' ) do if %%i leq %dropend% >>new\541.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<542.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<542.html ' ) do if %%i leq %dropend% >>new\542.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<543.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<543.html ' ) do if %%i leq %dropend% >>new\543.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<544.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<544.html ' ) do if %%i leq %dropend% >>new\544.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<545.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<545.html ' ) do if %%i leq %dropend% >>new\545.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<546.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<546.html ' ) do if %%i leq %dropend% >>new\546.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<547.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<547.html ' ) do if %%i leq %dropend% >>new\547.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<548.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<548.html ' ) do if %%i leq %dropend% >>new\548.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<549.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<549.html ' ) do if %%i leq %dropend% >>new\549.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<550.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<550.html ' ) do if %%i leq %dropend% >>new\550.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<551.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<551.html ' ) do if %%i leq %dropend% >>new\551.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<552.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<552.html ' ) do if %%i leq %dropend% >>new\552.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<553.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<553.html ' ) do if %%i leq %dropend% >>new\553.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<554.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<554.html ' ) do if %%i leq %dropend% >>new\554.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<555.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<555.html ' ) do if %%i leq %dropend% >>new\555.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<556.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<556.html ' ) do if %%i leq %dropend% >>new\556.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<557.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<557.html ' ) do if %%i leq %dropend% >>new\557.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<558.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<558.html ' ) do if %%i leq %dropend% >>new\558.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<559.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<559.html ' ) do if %%i leq %dropend% >>new\559.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<560.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<560.html ' ) do if %%i leq %dropend% >>new\560.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<561.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<561.html ' ) do if %%i leq %dropend% >>new\561.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<562.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<562.html ' ) do if %%i leq %dropend% >>new\562.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<563.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<563.html ' ) do if %%i leq %dropend% >>new\563.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<564.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<564.html ' ) do if %%i leq %dropend% >>new\564.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<565.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<565.html ' ) do if %%i leq %dropend% >>new\565.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<566.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<566.html ' ) do if %%i leq %dropend% >>new\566.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<567.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<567.html ' ) do if %%i leq %dropend% >>new\567.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<568.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<568.html ' ) do if %%i leq %dropend% >>new\568.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<569.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<569.html ' ) do if %%i leq %dropend% >>new\569.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<570.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<570.html ' ) do if %%i leq %dropend% >>new\570.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<571.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<571.html ' ) do if %%i leq %dropend% >>new\571.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<572.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<572.html ' ) do if %%i leq %dropend% >>new\572.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<573.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<573.html ' ) do if %%i leq %dropend% >>new\573.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<574.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<574.html ' ) do if %%i leq %dropend% >>new\574.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<575.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<575.html ' ) do if %%i leq %dropend% >>new\575.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<576.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<576.html ' ) do if %%i leq %dropend% >>new\576.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<577.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<577.html ' ) do if %%i leq %dropend% >>new\577.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<578.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<578.html ' ) do if %%i leq %dropend% >>new\578.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<579.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<579.html ' ) do if %%i leq %dropend% >>new\579.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<580.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<580.html ' ) do if %%i leq %dropend% >>new\580.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<581.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<581.html ' ) do if %%i leq %dropend% >>new\581.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<582.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<582.html ' ) do if %%i leq %dropend% >>new\582.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<583.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<583.html ' ) do if %%i leq %dropend% >>new\583.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<584.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<584.html ' ) do if %%i leq %dropend% >>new\584.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<585.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<585.html ' ) do if %%i leq %dropend% >>new\585.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<586.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<586.html ' ) do if %%i leq %dropend% >>new\586.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<587.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<587.html ' ) do if %%i leq %dropend% >>new\587.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<588.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<588.html ' ) do if %%i leq %dropend% >>new\588.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<589.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<589.html ' ) do if %%i leq %dropend% >>new\589.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<590.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<590.html ' ) do if %%i leq %dropend% >>new\590.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<591.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<591.html ' ) do if %%i leq %dropend% >>new\591.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<592.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<592.html ' ) do if %%i leq %dropend% >>new\592.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<593.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<593.html ' ) do if %%i leq %dropend% >>new\593.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<594.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<594.html ' ) do if %%i leq %dropend% >>new\594.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<595.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<595.html ' ) do if %%i leq %dropend% >>new\595.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<596.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<596.html ' ) do if %%i leq %dropend% >>new\596.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<597.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<597.html ' ) do if %%i leq %dropend% >>new\597.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<598.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<598.html ' ) do if %%i leq %dropend% >>new\598.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<599.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<599.html ' ) do if %%i leq %dropend% >>new\599.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<600.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<600.html ' ) do if %%i leq %dropend% >>new\600.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<601.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<601.html ' ) do if %%i leq %dropend% >>new\601.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<602.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<602.html ' ) do if %%i leq %dropend% >>new\602.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<603.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<603.html ' ) do if %%i leq %dropend% >>new\603.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<604.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<604.html ' ) do if %%i leq %dropend% >>new\604.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<605.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<605.html ' ) do if %%i leq %dropend% >>new\605.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<606.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<606.html ' ) do if %%i leq %dropend% >>new\606.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<607.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<607.html ' ) do if %%i leq %dropend% >>new\607.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<608.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<608.html ' ) do if %%i leq %dropend% >>new\608.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<609.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<609.html ' ) do if %%i leq %dropend% >>new\609.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<610.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<610.html ' ) do if %%i leq %dropend% >>new\610.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<611.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<611.html ' ) do if %%i leq %dropend% >>new\611.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<612.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<612.html ' ) do if %%i leq %dropend% >>new\612.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<613.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<613.html ' ) do if %%i leq %dropend% >>new\613.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<614.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<614.html ' ) do if %%i leq %dropend% >>new\614.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<615.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<615.html ' ) do if %%i leq %dropend% >>new\615.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<616.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<616.html ' ) do if %%i leq %dropend% >>new\616.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<617.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<617.html ' ) do if %%i leq %dropend% >>new\617.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<618.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<618.html ' ) do if %%i leq %dropend% >>new\618.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<619.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<619.html ' ) do if %%i leq %dropend% >>new\619.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<620.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<620.html ' ) do if %%i leq %dropend% >>new\620.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<621.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<621.html ' ) do if %%i leq %dropend% >>new\621.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<622.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<622.html ' ) do if %%i leq %dropend% >>new\622.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<623.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<623.html ' ) do if %%i leq %dropend% >>new\623.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<624.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<624.html ' ) do if %%i leq %dropend% >>new\624.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<625.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<625.html ' ) do if %%i leq %dropend% >>new\625.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<626.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<626.html ' ) do if %%i leq %dropend% >>new\626.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<627.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<627.html ' ) do if %%i leq %dropend% >>new\627.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<628.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<628.html ' ) do if %%i leq %dropend% >>new\628.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<629.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<629.html ' ) do if %%i leq %dropend% >>new\629.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<630.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<630.html ' ) do if %%i leq %dropend% >>new\630.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<631.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<631.html ' ) do if %%i leq %dropend% >>new\631.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<632.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<632.html ' ) do if %%i leq %dropend% >>new\632.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<633.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<633.html ' ) do if %%i leq %dropend% >>new\633.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<634.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<634.html ' ) do if %%i leq %dropend% >>new\634.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<635.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<635.html ' ) do if %%i leq %dropend% >>new\635.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<636.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<636.html ' ) do if %%i leq %dropend% >>new\636.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<637.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<637.html ' ) do if %%i leq %dropend% >>new\637.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<638.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<638.html ' ) do if %%i leq %dropend% >>new\638.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<639.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<639.html ' ) do if %%i leq %dropend% >>new\639.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<640.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<640.html ' ) do if %%i leq %dropend% >>new\640.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<641.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<641.html ' ) do if %%i leq %dropend% >>new\641.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<642.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<642.html ' ) do if %%i leq %dropend% >>new\642.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<643.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<643.html ' ) do if %%i leq %dropend% >>new\643.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<644.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<644.html ' ) do if %%i leq %dropend% >>new\644.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<645.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<645.html ' ) do if %%i leq %dropend% >>new\645.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<646.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<646.html ' ) do if %%i leq %dropend% >>new\646.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<647.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<647.html ' ) do if %%i leq %dropend% >>new\647.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<648.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<648.html ' ) do if %%i leq %dropend% >>new\648.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<649.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<649.html ' ) do if %%i leq %dropend% >>new\649.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<650.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<650.html ' ) do if %%i leq %dropend% >>new\650.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<651.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<651.html ' ) do if %%i leq %dropend% >>new\651.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<652.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<652.html ' ) do if %%i leq %dropend% >>new\652.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<653.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<653.html ' ) do if %%i leq %dropend% >>new\653.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<654.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<654.html ' ) do if %%i leq %dropend% >>new\654.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<655.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<655.html ' ) do if %%i leq %dropend% >>new\655.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<656.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<656.html ' ) do if %%i leq %dropend% >>new\656.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<657.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<657.html ' ) do if %%i leq %dropend% >>new\657.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<658.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<658.html ' ) do if %%i leq %dropend% >>new\658.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<659.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<659.html ' ) do if %%i leq %dropend% >>new\659.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<660.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<660.html ' ) do if %%i leq %dropend% >>new\660.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<661.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<661.html ' ) do if %%i leq %dropend% >>new\661.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<662.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<662.html ' ) do if %%i leq %dropend% >>new\662.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<663.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<663.html ' ) do if %%i leq %dropend% >>new\663.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<664.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<664.html ' ) do if %%i leq %dropend% >>new\664.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<665.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<665.html ' ) do if %%i leq %dropend% >>new\665.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<666.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<666.html ' ) do if %%i leq %dropend% >>new\666.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<667.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<667.html ' ) do if %%i leq %dropend% >>new\667.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<668.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<668.html ' ) do if %%i leq %dropend% >>new\668.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<669.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<669.html ' ) do if %%i leq %dropend% >>new\669.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<670.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<670.html ' ) do if %%i leq %dropend% >>new\670.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<671.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<671.html ' ) do if %%i leq %dropend% >>new\671.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<672.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<672.html ' ) do if %%i leq %dropend% >>new\672.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<673.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<673.html ' ) do if %%i leq %dropend% >>new\673.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<674.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<674.html ' ) do if %%i leq %dropend% >>new\674.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<675.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<675.html ' ) do if %%i leq %dropend% >>new\675.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<676.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<676.html ' ) do if %%i leq %dropend% >>new\676.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<677.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<677.html ' ) do if %%i leq %dropend% >>new\677.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<678.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<678.html ' ) do if %%i leq %dropend% >>new\678.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<679.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<679.html ' ) do if %%i leq %dropend% >>new\679.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<680.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<680.html ' ) do if %%i leq %dropend% >>new\680.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<681.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<681.html ' ) do if %%i leq %dropend% >>new\681.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<682.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<682.html ' ) do if %%i leq %dropend% >>new\682.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<683.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<683.html ' ) do if %%i leq %dropend% >>new\683.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<684.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<684.html ' ) do if %%i leq %dropend% >>new\684.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<685.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<685.html ' ) do if %%i leq %dropend% >>new\685.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<686.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<686.html ' ) do if %%i leq %dropend% >>new\686.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<687.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<687.html ' ) do if %%i leq %dropend% >>new\687.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<688.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<688.html ' ) do if %%i leq %dropend% >>new\688.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<689.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<689.html ' ) do if %%i leq %dropend% >>new\689.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<690.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<690.html ' ) do if %%i leq %dropend% >>new\690.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<691.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<691.html ' ) do if %%i leq %dropend% >>new\691.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<692.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<692.html ' ) do if %%i leq %dropend% >>new\692.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<693.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<693.html ' ) do if %%i leq %dropend% >>new\693.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<694.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<694.html ' ) do if %%i leq %dropend% >>new\694.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<695.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<695.html ' ) do if %%i leq %dropend% >>new\695.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<696.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<696.html ' ) do if %%i leq %dropend% >>new\696.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<697.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<697.html ' ) do if %%i leq %dropend% >>new\697.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<698.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<698.html ' ) do if %%i leq %dropend% >>new\698.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<699.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<699.html ' ) do if %%i leq %dropend% >>new\699.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<700.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<700.html ' ) do if %%i leq %dropend% >>new\700.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<701.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<701.html ' ) do if %%i leq %dropend% >>new\701.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<702.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<702.html ' ) do if %%i leq %dropend% >>new\702.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<703.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<703.html ' ) do if %%i leq %dropend% >>new\703.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<704.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<704.html ' ) do if %%i leq %dropend% >>new\704.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<705.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<705.html ' ) do if %%i leq %dropend% >>new\705.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<706.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<706.html ' ) do if %%i leq %dropend% >>new\706.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<707.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<707.html ' ) do if %%i leq %dropend% >>new\707.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<708.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<708.html ' ) do if %%i leq %dropend% >>new\708.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<709.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<709.html ' ) do if %%i leq %dropend% >>new\709.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<710.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<710.html ' ) do if %%i leq %dropend% >>new\710.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<711.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<711.html ' ) do if %%i leq %dropend% >>new\711.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<712.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<712.html ' ) do if %%i leq %dropend% >>new\712.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<713.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<713.html ' ) do if %%i leq %dropend% >>new\713.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<714.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<714.html ' ) do if %%i leq %dropend% >>new\714.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<715.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<715.html ' ) do if %%i leq %dropend% >>new\715.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<716.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<716.html ' ) do if %%i leq %dropend% >>new\716.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<717.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<717.html ' ) do if %%i leq %dropend% >>new\717.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<718.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<718.html ' ) do if %%i leq %dropend% >>new\718.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<719.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<719.html ' ) do if %%i leq %dropend% >>new\719.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<720.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<720.html ' ) do if %%i leq %dropend% >>new\720.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<721.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<721.html ' ) do if %%i leq %dropend% >>new\721.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<722.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<722.html ' ) do if %%i leq %dropend% >>new\722.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<723.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<723.html ' ) do if %%i leq %dropend% >>new\723.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<724.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<724.html ' ) do if %%i leq %dropend% >>new\724.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<725.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<725.html ' ) do if %%i leq %dropend% >>new\725.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<726.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<726.html ' ) do if %%i leq %dropend% >>new\726.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<727.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<727.html ' ) do if %%i leq %dropend% >>new\727.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<728.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<728.html ' ) do if %%i leq %dropend% >>new\728.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<729.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<729.html ' ) do if %%i leq %dropend% >>new\729.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<730.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<730.html ' ) do if %%i leq %dropend% >>new\730.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<731.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<731.html ' ) do if %%i leq %dropend% >>new\731.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<732.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<732.html ' ) do if %%i leq %dropend% >>new\732.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<733.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<733.html ' ) do if %%i leq %dropend% >>new\733.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<734.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<734.html ' ) do if %%i leq %dropend% >>new\734.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<735.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<735.html ' ) do if %%i leq %dropend% >>new\735.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<736.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<736.html ' ) do if %%i leq %dropend% >>new\736.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<737.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<737.html ' ) do if %%i leq %dropend% >>new\737.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<738.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<738.html ' ) do if %%i leq %dropend% >>new\738.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<739.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<739.html ' ) do if %%i leq %dropend% >>new\739.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<740.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<740.html ' ) do if %%i leq %dropend% >>new\740.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<741.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<741.html ' ) do if %%i leq %dropend% >>new\741.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<742.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<742.html ' ) do if %%i leq %dropend% >>new\742.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<743.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<743.html ' ) do if %%i leq %dropend% >>new\743.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<744.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<744.html ' ) do if %%i leq %dropend% >>new\744.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<745.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<745.html ' ) do if %%i leq %dropend% >>new\745.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<746.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<746.html ' ) do if %%i leq %dropend% >>new\746.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<747.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<747.html ' ) do if %%i leq %dropend% >>new\747.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<748.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<748.html ' ) do if %%i leq %dropend% >>new\748.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<749.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<749.html ' ) do if %%i leq %dropend% >>new\749.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<750.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<750.html ' ) do if %%i leq %dropend% >>new\750.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<751.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<751.html ' ) do if %%i leq %dropend% >>new\751.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<752.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<752.html ' ) do if %%i leq %dropend% >>new\752.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<753.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<753.html ' ) do if %%i leq %dropend% >>new\753.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<754.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<754.html ' ) do if %%i leq %dropend% >>new\754.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<755.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<755.html ' ) do if %%i leq %dropend% >>new\755.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<756.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<756.html ' ) do if %%i leq %dropend% >>new\756.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<757.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<757.html ' ) do if %%i leq %dropend% >>new\757.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<758.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<758.html ' ) do if %%i leq %dropend% >>new\758.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<759.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<759.html ' ) do if %%i leq %dropend% >>new\759.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<760.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<760.html ' ) do if %%i leq %dropend% >>new\760.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<761.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<761.html ' ) do if %%i leq %dropend% >>new\761.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<762.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<762.html ' ) do if %%i leq %dropend% >>new\762.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<763.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<763.html ' ) do if %%i leq %dropend% >>new\763.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<764.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<764.html ' ) do if %%i leq %dropend% >>new\764.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<765.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<765.html ' ) do if %%i leq %dropend% >>new\765.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<766.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<766.html ' ) do if %%i leq %dropend% >>new\766.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<767.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<767.html ' ) do if %%i leq %dropend% >>new\767.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<768.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<768.html ' ) do if %%i leq %dropend% >>new\768.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<769.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<769.html ' ) do if %%i leq %dropend% >>new\769.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<770.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<770.html ' ) do if %%i leq %dropend% >>new\770.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<771.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<771.html ' ) do if %%i leq %dropend% >>new\771.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<772.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<772.html ' ) do if %%i leq %dropend% >>new\772.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<773.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<773.html ' ) do if %%i leq %dropend% >>new\773.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<774.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<774.html ' ) do if %%i leq %dropend% >>new\774.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<775.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<775.html ' ) do if %%i leq %dropend% >>new\775.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<776.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<776.html ' ) do if %%i leq %dropend% >>new\776.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<777.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<777.html ' ) do if %%i leq %dropend% >>new\777.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<778.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<778.html ' ) do if %%i leq %dropend% >>new\778.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<779.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<779.html ' ) do if %%i leq %dropend% >>new\779.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<780.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<780.html ' ) do if %%i leq %dropend% >>new\780.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<781.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<781.html ' ) do if %%i leq %dropend% >>new\781.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<782.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<782.html ' ) do if %%i leq %dropend% >>new\782.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<783.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<783.html ' ) do if %%i leq %dropend% >>new\783.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<784.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<784.html ' ) do if %%i leq %dropend% >>new\784.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<785.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<785.html ' ) do if %%i leq %dropend% >>new\785.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<786.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<786.html ' ) do if %%i leq %dropend% >>new\786.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<787.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<787.html ' ) do if %%i leq %dropend% >>new\787.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<788.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<788.html ' ) do if %%i leq %dropend% >>new\788.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<789.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<789.html ' ) do if %%i leq %dropend% >>new\789.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<790.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<790.html ' ) do if %%i leq %dropend% >>new\790.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<791.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<791.html ' ) do if %%i leq %dropend% >>new\791.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<792.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<792.html ' ) do if %%i leq %dropend% >>new\792.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<793.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<793.html ' ) do if %%i leq %dropend% >>new\793.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<794.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<794.html ' ) do if %%i leq %dropend% >>new\794.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<795.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<795.html ' ) do if %%i leq %dropend% >>new\795.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<796.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<796.html ' ) do if %%i leq %dropend% >>new\796.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<797.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<797.html ' ) do if %%i leq %dropend% >>new\797.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<798.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<798.html ' ) do if %%i leq %dropend% >>new\798.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<799.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<799.html ' ) do if %%i leq %dropend% >>new\799.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<800.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<800.html ' ) do if %%i leq %dropend% >>new\800.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<801.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<801.html ' ) do if %%i leq %dropend% >>new\801.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<802.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<802.html ' ) do if %%i leq %dropend% >>new\802.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<803.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<803.html ' ) do if %%i leq %dropend% >>new\803.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<804.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<804.html ' ) do if %%i leq %dropend% >>new\804.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<805.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<805.html ' ) do if %%i leq %dropend% >>new\805.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<806.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<806.html ' ) do if %%i leq %dropend% >>new\806.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<807.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<807.html ' ) do if %%i leq %dropend% >>new\807.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<808.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<808.html ' ) do if %%i leq %dropend% >>new\808.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<809.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<809.html ' ) do if %%i leq %dropend% >>new\809.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<810.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<810.html ' ) do if %%i leq %dropend% >>new\810.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<811.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<811.html ' ) do if %%i leq %dropend% >>new\811.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<812.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<812.html ' ) do if %%i leq %dropend% >>new\812.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<813.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<813.html ' ) do if %%i leq %dropend% >>new\813.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<814.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<814.html ' ) do if %%i leq %dropend% >>new\814.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<815.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<815.html ' ) do if %%i leq %dropend% >>new\815.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<816.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<816.html ' ) do if %%i leq %dropend% >>new\816.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<817.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<817.html ' ) do if %%i leq %dropend% >>new\817.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<818.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<818.html ' ) do if %%i leq %dropend% >>new\818.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<819.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<819.html ' ) do if %%i leq %dropend% >>new\819.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<820.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<820.html ' ) do if %%i leq %dropend% >>new\820.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<821.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<821.html ' ) do if %%i leq %dropend% >>new\821.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<822.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<822.html ' ) do if %%i leq %dropend% >>new\822.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<823.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<823.html ' ) do if %%i leq %dropend% >>new\823.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<824.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<824.html ' ) do if %%i leq %dropend% >>new\824.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<825.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<825.html ' ) do if %%i leq %dropend% >>new\825.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<826.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<826.html ' ) do if %%i leq %dropend% >>new\826.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<827.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<827.html ' ) do if %%i leq %dropend% >>new\827.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<828.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<828.html ' ) do if %%i leq %dropend% >>new\828.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<829.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<829.html ' ) do if %%i leq %dropend% >>new\829.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<830.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<830.html ' ) do if %%i leq %dropend% >>new\830.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<831.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<831.html ' ) do if %%i leq %dropend% >>new\831.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<832.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<832.html ' ) do if %%i leq %dropend% >>new\832.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<833.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<833.html ' ) do if %%i leq %dropend% >>new\833.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<834.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<834.html ' ) do if %%i leq %dropend% >>new\834.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<835.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<835.html ' ) do if %%i leq %dropend% >>new\835.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<836.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<836.html ' ) do if %%i leq %dropend% >>new\836.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<837.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<837.html ' ) do if %%i leq %dropend% >>new\837.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<838.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<838.html ' ) do if %%i leq %dropend% >>new\838.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<839.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<839.html ' ) do if %%i leq %dropend% >>new\839.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<840.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<840.html ' ) do if %%i leq %dropend% >>new\840.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<841.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<841.html ' ) do if %%i leq %dropend% >>new\841.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<842.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<842.html ' ) do if %%i leq %dropend% >>new\842.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<843.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<843.html ' ) do if %%i leq %dropend% >>new\843.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<844.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<844.html ' ) do if %%i leq %dropend% >>new\844.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<845.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<845.html ' ) do if %%i leq %dropend% >>new\845.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<846.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<846.html ' ) do if %%i leq %dropend% >>new\846.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<847.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<847.html ' ) do if %%i leq %dropend% >>new\847.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<848.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<848.html ' ) do if %%i leq %dropend% >>new\848.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<849.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<849.html ' ) do if %%i leq %dropend% >>new\849.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<850.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<850.html ' ) do if %%i leq %dropend% >>new\850.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<851.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<851.html ' ) do if %%i leq %dropend% >>new\851.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<852.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<852.html ' ) do if %%i leq %dropend% >>new\852.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<853.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<853.html ' ) do if %%i leq %dropend% >>new\853.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<854.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<854.html ' ) do if %%i leq %dropend% >>new\854.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<855.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<855.html ' ) do if %%i leq %dropend% >>new\855.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<856.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<856.html ' ) do if %%i leq %dropend% >>new\856.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<857.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<857.html ' ) do if %%i leq %dropend% >>new\857.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<858.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<858.html ' ) do if %%i leq %dropend% >>new\858.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<859.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<859.html ' ) do if %%i leq %dropend% >>new\859.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<860.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<860.html ' ) do if %%i leq %dropend% >>new\860.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<861.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<861.html ' ) do if %%i leq %dropend% >>new\861.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<862.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<862.html ' ) do if %%i leq %dropend% >>new\862.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<863.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<863.html ' ) do if %%i leq %dropend% >>new\863.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<864.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<864.html ' ) do if %%i leq %dropend% >>new\864.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<865.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<865.html ' ) do if %%i leq %dropend% >>new\865.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<866.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<866.html ' ) do if %%i leq %dropend% >>new\866.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<867.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<867.html ' ) do if %%i leq %dropend% >>new\867.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<868.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<868.html ' ) do if %%i leq %dropend% >>new\868.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<869.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<869.html ' ) do if %%i leq %dropend% >>new\869.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<870.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<870.html ' ) do if %%i leq %dropend% >>new\870.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<871.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<871.html ' ) do if %%i leq %dropend% >>new\871.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<872.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<872.html ' ) do if %%i leq %dropend% >>new\872.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<873.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<873.html ' ) do if %%i leq %dropend% >>new\873.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<874.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<874.html ' ) do if %%i leq %dropend% >>new\874.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<875.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<875.html ' ) do if %%i leq %dropend% >>new\875.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<876.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<876.html ' ) do if %%i leq %dropend% >>new\876.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<877.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<877.html ' ) do if %%i leq %dropend% >>new\877.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<878.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<878.html ' ) do if %%i leq %dropend% >>new\878.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<879.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<879.html ' ) do if %%i leq %dropend% >>new\879.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<880.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<880.html ' ) do if %%i leq %dropend% >>new\880.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<881.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<881.html ' ) do if %%i leq %dropend% >>new\881.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<882.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<882.html ' ) do if %%i leq %dropend% >>new\882.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<883.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<883.html ' ) do if %%i leq %dropend% >>new\883.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<884.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<884.html ' ) do if %%i leq %dropend% >>new\884.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<885.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<885.html ' ) do if %%i leq %dropend% >>new\885.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<886.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<886.html ' ) do if %%i leq %dropend% >>new\886.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<887.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<887.html ' ) do if %%i leq %dropend% >>new\887.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<888.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<888.html ' ) do if %%i leq %dropend% >>new\888.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<889.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<889.html ' ) do if %%i leq %dropend% >>new\889.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<890.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<890.html ' ) do if %%i leq %dropend% >>new\890.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<891.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<891.html ' ) do if %%i leq %dropend% >>new\891.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<892.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<892.html ' ) do if %%i leq %dropend% >>new\892.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<893.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<893.html ' ) do if %%i leq %dropend% >>new\893.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<894.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<894.html ' ) do if %%i leq %dropend% >>new\894.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<895.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<895.html ' ) do if %%i leq %dropend% >>new\895.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<896.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<896.html ' ) do if %%i leq %dropend% >>new\896.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<897.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<897.html ' ) do if %%i leq %dropend% >>new\897.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<898.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<898.html ' ) do if %%i leq %dropend% >>new\898.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<899.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<899.html ' ) do if %%i leq %dropend% >>new\899.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<900.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<900.html ' ) do if %%i leq %dropend% >>new\900.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<901.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<901.html ' ) do if %%i leq %dropend% >>new\901.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<902.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<902.html ' ) do if %%i leq %dropend% >>new\902.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<903.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<903.html ' ) do if %%i leq %dropend% >>new\903.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<904.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<904.html ' ) do if %%i leq %dropend% >>new\904.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<905.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<905.html ' ) do if %%i leq %dropend% >>new\905.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<906.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<906.html ' ) do if %%i leq %dropend% >>new\906.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<907.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<907.html ' ) do if %%i leq %dropend% >>new\907.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<908.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<908.html ' ) do if %%i leq %dropend% >>new\908.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<909.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<909.html ' ) do if %%i leq %dropend% >>new\909.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<910.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<910.html ' ) do if %%i leq %dropend% >>new\910.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<911.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<911.html ' ) do if %%i leq %dropend% >>new\911.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<912.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<912.html ' ) do if %%i leq %dropend% >>new\912.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<913.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<913.html ' ) do if %%i leq %dropend% >>new\913.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<914.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<914.html ' ) do if %%i leq %dropend% >>new\914.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<915.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<915.html ' ) do if %%i leq %dropend% >>new\915.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<916.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<916.html ' ) do if %%i leq %dropend% >>new\916.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<917.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<917.html ' ) do if %%i leq %dropend% >>new\917.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<918.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<918.html ' ) do if %%i leq %dropend% >>new\918.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<919.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<919.html ' ) do if %%i leq %dropend% >>new\919.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<920.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<920.html ' ) do if %%i leq %dropend% >>new\920.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<921.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<921.html ' ) do if %%i leq %dropend% >>new\921.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<922.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<922.html ' ) do if %%i leq %dropend% >>new\922.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<923.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<923.html ' ) do if %%i leq %dropend% >>new\923.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<924.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<924.html ' ) do if %%i leq %dropend% >>new\924.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<925.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<925.html ' ) do if %%i leq %dropend% >>new\925.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<926.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<926.html ' ) do if %%i leq %dropend% >>new\926.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<927.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<927.html ' ) do if %%i leq %dropend% >>new\927.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<928.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<928.html ' ) do if %%i leq %dropend% >>new\928.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<929.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<929.html ' ) do if %%i leq %dropend% >>new\929.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<930.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<930.html ' ) do if %%i leq %dropend% >>new\930.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<931.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<931.html ' ) do if %%i leq %dropend% >>new\931.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<932.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<932.html ' ) do if %%i leq %dropend% >>new\932.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<933.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<933.html ' ) do if %%i leq %dropend% >>new\933.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<934.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<934.html ' ) do if %%i leq %dropend% >>new\934.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<935.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<935.html ' ) do if %%i leq %dropend% >>new\935.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<936.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<936.html ' ) do if %%i leq %dropend% >>new\936.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<937.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<937.html ' ) do if %%i leq %dropend% >>new\937.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<938.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<938.html ' ) do if %%i leq %dropend% >>new\938.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<939.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<939.html ' ) do if %%i leq %dropend% >>new\939.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<940.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<940.html ' ) do if %%i leq %dropend% >>new\940.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<941.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<941.html ' ) do if %%i leq %dropend% >>new\941.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<942.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<942.html ' ) do if %%i leq %dropend% >>new\942.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<943.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<943.html ' ) do if %%i leq %dropend% >>new\943.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<944.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<944.html ' ) do if %%i leq %dropend% >>new\944.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<945.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<945.html ' ) do if %%i leq %dropend% >>new\945.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<946.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<946.html ' ) do if %%i leq %dropend% >>new\946.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<947.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<947.html ' ) do if %%i leq %dropend% >>new\947.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<948.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<948.html ' ) do if %%i leq %dropend% >>new\948.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<949.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<949.html ' ) do if %%i leq %dropend% >>new\949.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<950.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<950.html ' ) do if %%i leq %dropend% >>new\950.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<951.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<951.html ' ) do if %%i leq %dropend% >>new\951.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<952.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<952.html ' ) do if %%i leq %dropend% >>new\952.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<953.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<953.html ' ) do if %%i leq %dropend% >>new\953.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<954.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<954.html ' ) do if %%i leq %dropend% >>new\954.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<955.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<955.html ' ) do if %%i leq %dropend% >>new\955.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<956.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<956.html ' ) do if %%i leq %dropend% >>new\956.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<957.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<957.html ' ) do if %%i leq %dropend% >>new\957.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<958.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<958.html ' ) do if %%i leq %dropend% >>new\958.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<959.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<959.html ' ) do if %%i leq %dropend% >>new\959.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<960.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<960.html ' ) do if %%i leq %dropend% >>new\960.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<961.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<961.html ' ) do if %%i leq %dropend% >>new\961.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<962.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<962.html ' ) do if %%i leq %dropend% >>new\962.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<963.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<963.html ' ) do if %%i leq %dropend% >>new\963.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<964.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<964.html ' ) do if %%i leq %dropend% >>new\964.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<965.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<965.html ' ) do if %%i leq %dropend% >>new\965.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<966.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<966.html ' ) do if %%i leq %dropend% >>new\966.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<967.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<967.html ' ) do if %%i leq %dropend% >>new\967.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<968.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<968.html ' ) do if %%i leq %dropend% >>new\968.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<969.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<969.html ' ) do if %%i leq %dropend% >>new\969.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<970.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<970.html ' ) do if %%i leq %dropend% >>new\970.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<971.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<971.html ' ) do if %%i leq %dropend% >>new\971.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<972.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<972.html ' ) do if %%i leq %dropend% >>new\972.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<973.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<973.html ' ) do if %%i leq %dropend% >>new\973.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<974.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<974.html ' ) do if %%i leq %dropend% >>new\974.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<975.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<975.html ' ) do if %%i leq %dropend% >>new\975.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<976.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<976.html ' ) do if %%i leq %dropend% >>new\976.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<977.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<977.html ' ) do if %%i leq %dropend% >>new\977.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<978.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<978.html ' ) do if %%i leq %dropend% >>new\978.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<979.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<979.html ' ) do if %%i leq %dropend% >>new\979.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<980.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<980.html ' ) do if %%i leq %dropend% >>new\980.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<981.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<981.html ' ) do if %%i leq %dropend% >>new\981.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<982.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<982.html ' ) do if %%i leq %dropend% >>new\982.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<983.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<983.html ' ) do if %%i leq %dropend% >>new\983.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<984.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<984.html ' ) do if %%i leq %dropend% >>new\984.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<985.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<985.html ' ) do if %%i leq %dropend% >>new\985.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<986.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<986.html ' ) do if %%i leq %dropend% >>new\986.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<987.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<987.html ' ) do if %%i leq %dropend% >>new\987.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<988.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<988.html ' ) do if %%i leq %dropend% >>new\988.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<989.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<989.html ' ) do if %%i leq %dropend% >>new\989.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<990.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<990.html ' ) do if %%i leq %dropend% >>new\990.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<991.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<991.html ' ) do if %%i leq %dropend% >>new\991.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<992.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<992.html ' ) do if %%i leq %dropend% >>new\992.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<993.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<993.html ' ) do if %%i leq %dropend% >>new\993.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<994.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<994.html ' ) do if %%i leq %dropend% >>new\994.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<995.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<995.html ' ) do if %%i leq %dropend% >>new\995.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<996.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<996.html ' ) do if %%i leq %dropend% >>new\996.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<997.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<997.html ' ) do if %%i leq %dropend% >>new\997.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<998.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<998.html ' ) do if %%i leq %dropend% >>new\998.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<999.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<999.html ' ) do if %%i leq %dropend% >>new\999.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1000.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1000.html ' ) do if %%i leq %dropend% >>new\1000.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1001.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1001.html ' ) do if %%i leq %dropend% >>new\1001.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1002.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1002.html ' ) do if %%i leq %dropend% >>new\1002.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1003.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1003.html ' ) do if %%i leq %dropend% >>new\1003.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1004.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1004.html ' ) do if %%i leq %dropend% >>new\1004.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1005.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1005.html ' ) do if %%i leq %dropend% >>new\1005.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1006.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1006.html ' ) do if %%i leq %dropend% >>new\1006.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1007.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1007.html ' ) do if %%i leq %dropend% >>new\1007.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1008.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1008.html ' ) do if %%i leq %dropend% >>new\1008.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1009.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1009.html ' ) do if %%i leq %dropend% >>new\1009.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1010.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1010.html ' ) do if %%i leq %dropend% >>new\1010.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1011.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1011.html ' ) do if %%i leq %dropend% >>new\1011.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1012.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1012.html ' ) do if %%i leq %dropend% >>new\1012.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1013.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1013.html ' ) do if %%i leq %dropend% >>new\1013.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1014.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1014.html ' ) do if %%i leq %dropend% >>new\1014.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1015.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1015.html ' ) do if %%i leq %dropend% >>new\1015.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1016.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1016.html ' ) do if %%i leq %dropend% >>new\1016.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1017.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1017.html ' ) do if %%i leq %dropend% >>new\1017.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1018.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1018.html ' ) do if %%i leq %dropend% >>new\1018.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1019.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1019.html ' ) do if %%i leq %dropend% >>new\1019.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1020.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1020.html ' ) do if %%i leq %dropend% >>new\1020.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1021.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1021.html ' ) do if %%i leq %dropend% >>new\1021.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1022.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1022.html ' ) do if %%i leq %dropend% >>new\1022.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1023.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1023.html ' ) do if %%i leq %dropend% >>new\1023.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1024.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1024.html ' ) do if %%i leq %dropend% >>new\1024.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1025.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1025.html ' ) do if %%i leq %dropend% >>new\1025.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1026.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1026.html ' ) do if %%i leq %dropend% >>new\1026.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1027.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1027.html ' ) do if %%i leq %dropend% >>new\1027.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1028.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1028.html ' ) do if %%i leq %dropend% >>new\1028.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1029.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1029.html ' ) do if %%i leq %dropend% >>new\1029.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1030.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1030.html ' ) do if %%i leq %dropend% >>new\1030.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1031.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1031.html ' ) do if %%i leq %dropend% >>new\1031.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1032.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1032.html ' ) do if %%i leq %dropend% >>new\1032.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1033.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1033.html ' ) do if %%i leq %dropend% >>new\1033.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1034.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1034.html ' ) do if %%i leq %dropend% >>new\1034.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1035.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1035.html ' ) do if %%i leq %dropend% >>new\1035.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1036.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1036.html ' ) do if %%i leq %dropend% >>new\1036.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1037.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1037.html ' ) do if %%i leq %dropend% >>new\1037.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1038.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1038.html ' ) do if %%i leq %dropend% >>new\1038.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1039.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1039.html ' ) do if %%i leq %dropend% >>new\1039.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1040.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1040.html ' ) do if %%i leq %dropend% >>new\1040.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1041.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1041.html ' ) do if %%i leq %dropend% >>new\1041.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1042.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1042.html ' ) do if %%i leq %dropend% >>new\1042.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1043.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1043.html ' ) do if %%i leq %dropend% >>new\1043.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1044.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1044.html ' ) do if %%i leq %dropend% >>new\1044.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1045.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1045.html ' ) do if %%i leq %dropend% >>new\1045.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1046.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1046.html ' ) do if %%i leq %dropend% >>new\1046.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1047.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1047.html ' ) do if %%i leq %dropend% >>new\1047.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1048.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1048.html ' ) do if %%i leq %dropend% >>new\1048.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1049.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1049.html ' ) do if %%i leq %dropend% >>new\1049.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1050.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1050.html ' ) do if %%i leq %dropend% >>new\1050.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1051.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1051.html ' ) do if %%i leq %dropend% >>new\1051.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1052.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1052.html ' ) do if %%i leq %dropend% >>new\1052.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1053.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1053.html ' ) do if %%i leq %dropend% >>new\1053.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1054.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1054.html ' ) do if %%i leq %dropend% >>new\1054.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1055.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1055.html ' ) do if %%i leq %dropend% >>new\1055.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1056.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1056.html ' ) do if %%i leq %dropend% >>new\1056.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1057.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1057.html ' ) do if %%i leq %dropend% >>new\1057.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1058.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1058.html ' ) do if %%i leq %dropend% >>new\1058.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1059.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1059.html ' ) do if %%i leq %dropend% >>new\1059.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1060.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1060.html ' ) do if %%i leq %dropend% >>new\1060.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1061.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1061.html ' ) do if %%i leq %dropend% >>new\1061.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1062.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1062.html ' ) do if %%i leq %dropend% >>new\1062.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1063.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1063.html ' ) do if %%i leq %dropend% >>new\1063.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1064.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1064.html ' ) do if %%i leq %dropend% >>new\1064.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1065.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1065.html ' ) do if %%i leq %dropend% >>new\1065.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1066.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1066.html ' ) do if %%i leq %dropend% >>new\1066.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1067.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1067.html ' ) do if %%i leq %dropend% >>new\1067.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1068.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1068.html ' ) do if %%i leq %dropend% >>new\1068.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1069.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1069.html ' ) do if %%i leq %dropend% >>new\1069.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1070.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1070.html ' ) do if %%i leq %dropend% >>new\1070.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1071.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1071.html ' ) do if %%i leq %dropend% >>new\1071.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1072.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1072.html ' ) do if %%i leq %dropend% >>new\1072.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1073.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1073.html ' ) do if %%i leq %dropend% >>new\1073.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1074.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1074.html ' ) do if %%i leq %dropend% >>new\1074.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1075.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1075.html ' ) do if %%i leq %dropend% >>new\1075.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1076.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1076.html ' ) do if %%i leq %dropend% >>new\1076.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1077.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1077.html ' ) do if %%i leq %dropend% >>new\1077.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1078.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1078.html ' ) do if %%i leq %dropend% >>new\1078.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1079.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1079.html ' ) do if %%i leq %dropend% >>new\1079.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1080.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1080.html ' ) do if %%i leq %dropend% >>new\1080.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1081.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1081.html ' ) do if %%i leq %dropend% >>new\1081.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1082.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1082.html ' ) do if %%i leq %dropend% >>new\1082.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1083.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1083.html ' ) do if %%i leq %dropend% >>new\1083.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1084.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1084.html ' ) do if %%i leq %dropend% >>new\1084.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1085.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1085.html ' ) do if %%i leq %dropend% >>new\1085.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1086.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1086.html ' ) do if %%i leq %dropend% >>new\1086.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1087.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1087.html ' ) do if %%i leq %dropend% >>new\1087.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1088.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1088.html ' ) do if %%i leq %dropend% >>new\1088.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1089.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1089.html ' ) do if %%i leq %dropend% >>new\1089.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1090.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1090.html ' ) do if %%i leq %dropend% >>new\1090.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1091.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1091.html ' ) do if %%i leq %dropend% >>new\1091.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1092.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1092.html ' ) do if %%i leq %dropend% >>new\1092.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1093.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1093.html ' ) do if %%i leq %dropend% >>new\1093.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1094.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1094.html ' ) do if %%i leq %dropend% >>new\1094.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1095.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1095.html ' ) do if %%i leq %dropend% >>new\1095.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1096.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1096.html ' ) do if %%i leq %dropend% >>new\1096.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1097.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1097.html ' ) do if %%i leq %dropend% >>new\1097.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1098.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1098.html ' ) do if %%i leq %dropend% >>new\1098.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1099.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1099.html ' ) do if %%i leq %dropend% >>new\1099.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1100.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1100.html ' ) do if %%i leq %dropend% >>new\1100.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1101.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1101.html ' ) do if %%i leq %dropend% >>new\1101.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1102.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1102.html ' ) do if %%i leq %dropend% >>new\1102.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1103.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1103.html ' ) do if %%i leq %dropend% >>new\1103.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1104.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1104.html ' ) do if %%i leq %dropend% >>new\1104.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1105.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1105.html ' ) do if %%i leq %dropend% >>new\1105.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1106.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1106.html ' ) do if %%i leq %dropend% >>new\1106.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1107.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1107.html ' ) do if %%i leq %dropend% >>new\1107.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1108.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1108.html ' ) do if %%i leq %dropend% >>new\1108.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1109.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1109.html ' ) do if %%i leq %dropend% >>new\1109.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1110.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1110.html ' ) do if %%i leq %dropend% >>new\1110.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1111.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1111.html ' ) do if %%i leq %dropend% >>new\1111.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1112.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1112.html ' ) do if %%i leq %dropend% >>new\1112.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1113.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1113.html ' ) do if %%i leq %dropend% >>new\1113.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1114.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1114.html ' ) do if %%i leq %dropend% >>new\1114.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1115.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1115.html ' ) do if %%i leq %dropend% >>new\1115.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1116.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1116.html ' ) do if %%i leq %dropend% >>new\1116.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1117.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1117.html ' ) do if %%i leq %dropend% >>new\1117.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1118.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1118.html ' ) do if %%i leq %dropend% >>new\1118.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1119.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1119.html ' ) do if %%i leq %dropend% >>new\1119.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1120.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1120.html ' ) do if %%i leq %dropend% >>new\1120.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1121.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1121.html ' ) do if %%i leq %dropend% >>new\1121.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1122.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1122.html ' ) do if %%i leq %dropend% >>new\1122.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1123.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1123.html ' ) do if %%i leq %dropend% >>new\1123.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1124.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1124.html ' ) do if %%i leq %dropend% >>new\1124.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1125.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1125.html ' ) do if %%i leq %dropend% >>new\1125.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1126.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1126.html ' ) do if %%i leq %dropend% >>new\1126.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1127.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1127.html ' ) do if %%i leq %dropend% >>new\1127.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1128.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1128.html ' ) do if %%i leq %dropend% >>new\1128.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1129.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1129.html ' ) do if %%i leq %dropend% >>new\1129.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1130.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1130.html ' ) do if %%i leq %dropend% >>new\1130.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1131.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1131.html ' ) do if %%i leq %dropend% >>new\1131.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1132.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1132.html ' ) do if %%i leq %dropend% >>new\1132.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1133.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1133.html ' ) do if %%i leq %dropend% >>new\1133.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1134.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1134.html ' ) do if %%i leq %dropend% >>new\1134.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1135.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1135.html ' ) do if %%i leq %dropend% >>new\1135.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1136.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1136.html ' ) do if %%i leq %dropend% >>new\1136.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1137.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1137.html ' ) do if %%i leq %dropend% >>new\1137.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1138.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1138.html ' ) do if %%i leq %dropend% >>new\1138.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1139.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1139.html ' ) do if %%i leq %dropend% >>new\1139.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1140.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1140.html ' ) do if %%i leq %dropend% >>new\1140.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1141.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1141.html ' ) do if %%i leq %dropend% >>new\1141.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1142.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1142.html ' ) do if %%i leq %dropend% >>new\1142.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1143.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1143.html ' ) do if %%i leq %dropend% >>new\1143.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1144.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1144.html ' ) do if %%i leq %dropend% >>new\1144.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1145.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1145.html ' ) do if %%i leq %dropend% >>new\1145.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1146.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1146.html ' ) do if %%i leq %dropend% >>new\1146.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1147.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1147.html ' ) do if %%i leq %dropend% >>new\1147.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1148.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1148.html ' ) do if %%i leq %dropend% >>new\1148.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1149.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1149.html ' ) do if %%i leq %dropend% >>new\1149.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1150.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1150.html ' ) do if %%i leq %dropend% >>new\1150.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1151.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1151.html ' ) do if %%i leq %dropend% >>new\1151.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1152.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1152.html ' ) do if %%i leq %dropend% >>new\1152.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1153.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1153.html ' ) do if %%i leq %dropend% >>new\1153.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1154.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1154.html ' ) do if %%i leq %dropend% >>new\1154.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1155.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1155.html ' ) do if %%i leq %dropend% >>new\1155.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1156.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1156.html ' ) do if %%i leq %dropend% >>new\1156.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1157.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1157.html ' ) do if %%i leq %dropend% >>new\1157.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1158.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1158.html ' ) do if %%i leq %dropend% >>new\1158.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1159.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1159.html ' ) do if %%i leq %dropend% >>new\1159.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1160.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1160.html ' ) do if %%i leq %dropend% >>new\1160.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1161.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1161.html ' ) do if %%i leq %dropend% >>new\1161.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1162.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1162.html ' ) do if %%i leq %dropend% >>new\1162.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1163.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1163.html ' ) do if %%i leq %dropend% >>new\1163.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1164.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1164.html ' ) do if %%i leq %dropend% >>new\1164.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1165.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1165.html ' ) do if %%i leq %dropend% >>new\1165.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1166.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1166.html ' ) do if %%i leq %dropend% >>new\1166.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1167.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1167.html ' ) do if %%i leq %dropend% >>new\1167.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1168.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1168.html ' ) do if %%i leq %dropend% >>new\1168.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1169.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1169.html ' ) do if %%i leq %dropend% >>new\1169.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1170.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1170.html ' ) do if %%i leq %dropend% >>new\1170.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1171.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1171.html ' ) do if %%i leq %dropend% >>new\1171.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1172.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1172.html ' ) do if %%i leq %dropend% >>new\1172.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1173.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1173.html ' ) do if %%i leq %dropend% >>new\1173.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1174.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1174.html ' ) do if %%i leq %dropend% >>new\1174.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1175.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1175.html ' ) do if %%i leq %dropend% >>new\1175.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1176.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1176.html ' ) do if %%i leq %dropend% >>new\1176.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1177.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1177.html ' ) do if %%i leq %dropend% >>new\1177.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1178.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1178.html ' ) do if %%i leq %dropend% >>new\1178.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1179.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1179.html ' ) do if %%i leq %dropend% >>new\1179.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1180.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1180.html ' ) do if %%i leq %dropend% >>new\1180.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1181.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1181.html ' ) do if %%i leq %dropend% >>new\1181.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1182.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1182.html ' ) do if %%i leq %dropend% >>new\1182.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1183.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1183.html ' ) do if %%i leq %dropend% >>new\1183.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1184.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1184.html ' ) do if %%i leq %dropend% >>new\1184.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1185.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1185.html ' ) do if %%i leq %dropend% >>new\1185.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1186.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1186.html ' ) do if %%i leq %dropend% >>new\1186.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1187.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1187.html ' ) do if %%i leq %dropend% >>new\1187.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1188.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1188.html ' ) do if %%i leq %dropend% >>new\1188.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1189.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1189.html ' ) do if %%i leq %dropend% >>new\1189.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1190.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1190.html ' ) do if %%i leq %dropend% >>new\1190.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1191.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1191.html ' ) do if %%i leq %dropend% >>new\1191.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1192.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1192.html ' ) do if %%i leq %dropend% >>new\1192.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1193.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1193.html ' ) do if %%i leq %dropend% >>new\1193.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1194.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1194.html ' ) do if %%i leq %dropend% >>new\1194.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1195.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1195.html ' ) do if %%i leq %dropend% >>new\1195.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1196.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1196.html ' ) do if %%i leq %dropend% >>new\1196.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1197.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1197.html ' ) do if %%i leq %dropend% >>new\1197.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1198.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1198.html ' ) do if %%i leq %dropend% >>new\1198.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1199.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1199.html ' ) do if %%i leq %dropend% >>new\1199.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1200.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1200.html ' ) do if %%i leq %dropend% >>new\1200.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1201.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1201.html ' ) do if %%i leq %dropend% >>new\1201.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1202.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1202.html ' ) do if %%i leq %dropend% >>new\1202.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1203.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1203.html ' ) do if %%i leq %dropend% >>new\1203.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1204.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1204.html ' ) do if %%i leq %dropend% >>new\1204.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1205.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1205.html ' ) do if %%i leq %dropend% >>new\1205.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1206.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1206.html ' ) do if %%i leq %dropend% >>new\1206.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1207.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1207.html ' ) do if %%i leq %dropend% >>new\1207.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1208.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1208.html ' ) do if %%i leq %dropend% >>new\1208.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1209.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1209.html ' ) do if %%i leq %dropend% >>new\1209.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1210.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1210.html ' ) do if %%i leq %dropend% >>new\1210.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1211.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1211.html ' ) do if %%i leq %dropend% >>new\1211.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1212.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1212.html ' ) do if %%i leq %dropend% >>new\1212.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1213.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1213.html ' ) do if %%i leq %dropend% >>new\1213.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1214.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1214.html ' ) do if %%i leq %dropend% >>new\1214.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1215.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1215.html ' ) do if %%i leq %dropend% >>new\1215.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1216.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1216.html ' ) do if %%i leq %dropend% >>new\1216.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1217.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1217.html ' ) do if %%i leq %dropend% >>new\1217.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1218.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1218.html ' ) do if %%i leq %dropend% >>new\1218.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1219.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1219.html ' ) do if %%i leq %dropend% >>new\1219.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1220.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1220.html ' ) do if %%i leq %dropend% >>new\1220.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1221.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1221.html ' ) do if %%i leq %dropend% >>new\1221.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1222.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1222.html ' ) do if %%i leq %dropend% >>new\1222.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1223.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1223.html ' ) do if %%i leq %dropend% >>new\1223.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1224.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1224.html ' ) do if %%i leq %dropend% >>new\1224.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1225.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1225.html ' ) do if %%i leq %dropend% >>new\1225.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1226.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1226.html ' ) do if %%i leq %dropend% >>new\1226.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1227.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1227.html ' ) do if %%i leq %dropend% >>new\1227.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1228.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1228.html ' ) do if %%i leq %dropend% >>new\1228.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1229.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1229.html ' ) do if %%i leq %dropend% >>new\1229.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1230.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1230.html ' ) do if %%i leq %dropend% >>new\1230.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1231.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1231.html ' ) do if %%i leq %dropend% >>new\1231.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1232.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1232.html ' ) do if %%i leq %dropend% >>new\1232.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1233.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1233.html ' ) do if %%i leq %dropend% >>new\1233.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1234.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1234.html ' ) do if %%i leq %dropend% >>new\1234.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1235.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1235.html ' ) do if %%i leq %dropend% >>new\1235.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1236.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1236.html ' ) do if %%i leq %dropend% >>new\1236.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1237.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1237.html ' ) do if %%i leq %dropend% >>new\1237.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1238.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1238.html ' ) do if %%i leq %dropend% >>new\1238.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1239.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1239.html ' ) do if %%i leq %dropend% >>new\1239.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1240.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1240.html ' ) do if %%i leq %dropend% >>new\1240.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1241.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1241.html ' ) do if %%i leq %dropend% >>new\1241.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1242.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1242.html ' ) do if %%i leq %dropend% >>new\1242.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1243.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1243.html ' ) do if %%i leq %dropend% >>new\1243.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1244.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1244.html ' ) do if %%i leq %dropend% >>new\1244.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1245.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1245.html ' ) do if %%i leq %dropend% >>new\1245.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1246.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1246.html ' ) do if %%i leq %dropend% >>new\1246.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1247.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1247.html ' ) do if %%i leq %dropend% >>new\1247.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1248.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1248.html ' ) do if %%i leq %dropend% >>new\1248.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1249.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1249.html ' ) do if %%i leq %dropend% >>new\1249.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1250.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1250.html ' ) do if %%i leq %dropend% >>new\1250.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1251.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1251.html ' ) do if %%i leq %dropend% >>new\1251.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1252.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1252.html ' ) do if %%i leq %dropend% >>new\1252.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1253.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1253.html ' ) do if %%i leq %dropend% >>new\1253.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1254.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1254.html ' ) do if %%i leq %dropend% >>new\1254.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1255.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1255.html ' ) do if %%i leq %dropend% >>new\1255.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1256.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1256.html ' ) do if %%i leq %dropend% >>new\1256.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1257.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1257.html ' ) do if %%i leq %dropend% >>new\1257.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1258.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1258.html ' ) do if %%i leq %dropend% >>new\1258.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1259.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1259.html ' ) do if %%i leq %dropend% >>new\1259.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1260.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1260.html ' ) do if %%i leq %dropend% >>new\1260.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1261.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1261.html ' ) do if %%i leq %dropend% >>new\1261.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1262.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1262.html ' ) do if %%i leq %dropend% >>new\1262.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1263.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1263.html ' ) do if %%i leq %dropend% >>new\1263.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1264.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1264.html ' ) do if %%i leq %dropend% >>new\1264.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1265.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1265.html ' ) do if %%i leq %dropend% >>new\1265.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1266.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1266.html ' ) do if %%i leq %dropend% >>new\1266.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1267.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1267.html ' ) do if %%i leq %dropend% >>new\1267.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1268.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1268.html ' ) do if %%i leq %dropend% >>new\1268.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1269.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1269.html ' ) do if %%i leq %dropend% >>new\1269.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1270.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1270.html ' ) do if %%i leq %dropend% >>new\1270.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1271.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1271.html ' ) do if %%i leq %dropend% >>new\1271.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1272.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1272.html ' ) do if %%i leq %dropend% >>new\1272.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1273.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1273.html ' ) do if %%i leq %dropend% >>new\1273.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1274.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1274.html ' ) do if %%i leq %dropend% >>new\1274.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1275.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1275.html ' ) do if %%i leq %dropend% >>new\1275.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1276.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1276.html ' ) do if %%i leq %dropend% >>new\1276.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1277.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1277.html ' ) do if %%i leq %dropend% >>new\1277.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1278.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1278.html ' ) do if %%i leq %dropend% >>new\1278.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1279.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1279.html ' ) do if %%i leq %dropend% >>new\1279.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1280.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1280.html ' ) do if %%i leq %dropend% >>new\1280.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1281.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1281.html ' ) do if %%i leq %dropend% >>new\1281.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1282.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1282.html ' ) do if %%i leq %dropend% >>new\1282.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1283.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1283.html ' ) do if %%i leq %dropend% >>new\1283.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1284.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1284.html ' ) do if %%i leq %dropend% >>new\1284.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1285.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1285.html ' ) do if %%i leq %dropend% >>new\1285.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1286.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1286.html ' ) do if %%i leq %dropend% >>new\1286.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1287.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1287.html ' ) do if %%i leq %dropend% >>new\1287.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1288.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1288.html ' ) do if %%i leq %dropend% >>new\1288.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1289.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1289.html ' ) do if %%i leq %dropend% >>new\1289.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1290.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1290.html ' ) do if %%i leq %dropend% >>new\1290.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1291.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1291.html ' ) do if %%i leq %dropend% >>new\1291.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1292.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1292.html ' ) do if %%i leq %dropend% >>new\1292.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1293.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1293.html ' ) do if %%i leq %dropend% >>new\1293.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1294.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1294.html ' ) do if %%i leq %dropend% >>new\1294.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1295.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1295.html ' ) do if %%i leq %dropend% >>new\1295.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1296.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1296.html ' ) do if %%i leq %dropend% >>new\1296.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1297.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1297.html ' ) do if %%i leq %dropend% >>new\1297.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1298.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1298.html ' ) do if %%i leq %dropend% >>new\1298.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1299.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1299.html ' ) do if %%i leq %dropend% >>new\1299.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1300.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1300.html ' ) do if %%i leq %dropend% >>new\1300.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1301.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1301.html ' ) do if %%i leq %dropend% >>new\1301.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1302.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1302.html ' ) do if %%i leq %dropend% >>new\1302.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1303.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1303.html ' ) do if %%i leq %dropend% >>new\1303.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1304.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1304.html ' ) do if %%i leq %dropend% >>new\1304.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1305.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1305.html ' ) do if %%i leq %dropend% >>new\1305.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1306.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1306.html ' ) do if %%i leq %dropend% >>new\1306.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1307.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1307.html ' ) do if %%i leq %dropend% >>new\1307.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1308.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1308.html ' ) do if %%i leq %dropend% >>new\1308.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1309.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1309.html ' ) do if %%i leq %dropend% >>new\1309.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1310.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1310.html ' ) do if %%i leq %dropend% >>new\1310.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1311.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1311.html ' ) do if %%i leq %dropend% >>new\1311.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1312.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1312.html ' ) do if %%i leq %dropend% >>new\1312.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1313.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1313.html ' ) do if %%i leq %dropend% >>new\1313.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1314.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1314.html ' ) do if %%i leq %dropend% >>new\1314.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1315.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1315.html ' ) do if %%i leq %dropend% >>new\1315.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1316.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1316.html ' ) do if %%i leq %dropend% >>new\1316.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1317.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1317.html ' ) do if %%i leq %dropend% >>new\1317.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1318.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1318.html ' ) do if %%i leq %dropend% >>new\1318.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1319.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1319.html ' ) do if %%i leq %dropend% >>new\1319.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1320.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1320.html ' ) do if %%i leq %dropend% >>new\1320.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1321.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1321.html ' ) do if %%i leq %dropend% >>new\1321.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1322.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1322.html ' ) do if %%i leq %dropend% >>new\1322.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1323.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1323.html ' ) do if %%i leq %dropend% >>new\1323.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1324.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1324.html ' ) do if %%i leq %dropend% >>new\1324.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1325.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1325.html ' ) do if %%i leq %dropend% >>new\1325.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1326.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1326.html ' ) do if %%i leq %dropend% >>new\1326.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1327.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1327.html ' ) do if %%i leq %dropend% >>new\1327.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1328.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1328.html ' ) do if %%i leq %dropend% >>new\1328.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1329.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1329.html ' ) do if %%i leq %dropend% >>new\1329.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1330.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1330.html ' ) do if %%i leq %dropend% >>new\1330.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1331.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1331.html ' ) do if %%i leq %dropend% >>new\1331.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1332.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1332.html ' ) do if %%i leq %dropend% >>new\1332.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1333.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1333.html ' ) do if %%i leq %dropend% >>new\1333.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1334.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1334.html ' ) do if %%i leq %dropend% >>new\1334.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1335.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1335.html ' ) do if %%i leq %dropend% >>new\1335.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1336.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1336.html ' ) do if %%i leq %dropend% >>new\1336.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1337.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1337.html ' ) do if %%i leq %dropend% >>new\1337.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1338.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1338.html ' ) do if %%i leq %dropend% >>new\1338.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1339.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1339.html ' ) do if %%i leq %dropend% >>new\1339.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1340.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1340.html ' ) do if %%i leq %dropend% >>new\1340.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1341.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1341.html ' ) do if %%i leq %dropend% >>new\1341.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1342.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1342.html ' ) do if %%i leq %dropend% >>new\1342.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1343.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1343.html ' ) do if %%i leq %dropend% >>new\1343.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1344.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1344.html ' ) do if %%i leq %dropend% >>new\1344.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1345.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1345.html ' ) do if %%i leq %dropend% >>new\1345.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1346.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1346.html ' ) do if %%i leq %dropend% >>new\1346.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1347.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1347.html ' ) do if %%i leq %dropend% >>new\1347.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1348.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1348.html ' ) do if %%i leq %dropend% >>new\1348.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1349.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1349.html ' ) do if %%i leq %dropend% >>new\1349.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1350.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1350.html ' ) do if %%i leq %dropend% >>new\1350.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1351.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1351.html ' ) do if %%i leq %dropend% >>new\1351.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1352.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1352.html ' ) do if %%i leq %dropend% >>new\1352.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1353.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1353.html ' ) do if %%i leq %dropend% >>new\1353.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1354.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1354.html ' ) do if %%i leq %dropend% >>new\1354.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1355.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1355.html ' ) do if %%i leq %dropend% >>new\1355.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1356.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1356.html ' ) do if %%i leq %dropend% >>new\1356.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1357.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1357.html ' ) do if %%i leq %dropend% >>new\1357.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1358.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1358.html ' ) do if %%i leq %dropend% >>new\1358.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1359.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1359.html ' ) do if %%i leq %dropend% >>new\1359.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1360.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1360.html ' ) do if %%i leq %dropend% >>new\1360.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1361.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1361.html ' ) do if %%i leq %dropend% >>new\1361.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1362.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1362.html ' ) do if %%i leq %dropend% >>new\1362.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1363.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1363.html ' ) do if %%i leq %dropend% >>new\1363.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1364.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1364.html ' ) do if %%i leq %dropend% >>new\1364.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1365.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1365.html ' ) do if %%i leq %dropend% >>new\1365.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1366.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1366.html ' ) do if %%i leq %dropend% >>new\1366.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1367.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1367.html ' ) do if %%i leq %dropend% >>new\1367.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1368.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1368.html ' ) do if %%i leq %dropend% >>new\1368.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1369.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1369.html ' ) do if %%i leq %dropend% >>new\1369.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1370.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1370.html ' ) do if %%i leq %dropend% >>new\1370.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1371.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1371.html ' ) do if %%i leq %dropend% >>new\1371.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1372.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1372.html ' ) do if %%i leq %dropend% >>new\1372.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1373.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1373.html ' ) do if %%i leq %dropend% >>new\1373.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1374.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1374.html ' ) do if %%i leq %dropend% >>new\1374.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1375.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1375.html ' ) do if %%i leq %dropend% >>new\1375.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1376.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1376.html ' ) do if %%i leq %dropend% >>new\1376.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1377.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1377.html ' ) do if %%i leq %dropend% >>new\1377.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1378.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1378.html ' ) do if %%i leq %dropend% >>new\1378.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1379.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1379.html ' ) do if %%i leq %dropend% >>new\1379.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1380.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1380.html ' ) do if %%i leq %dropend% >>new\1380.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1381.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1381.html ' ) do if %%i leq %dropend% >>new\1381.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1382.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1382.html ' ) do if %%i leq %dropend% >>new\1382.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1383.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1383.html ' ) do if %%i leq %dropend% >>new\1383.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1384.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1384.html ' ) do if %%i leq %dropend% >>new\1384.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1385.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1385.html ' ) do if %%i leq %dropend% >>new\1385.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1386.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1386.html ' ) do if %%i leq %dropend% >>new\1386.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1387.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1387.html ' ) do if %%i leq %dropend% >>new\1387.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1388.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1388.html ' ) do if %%i leq %dropend% >>new\1388.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1389.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1389.html ' ) do if %%i leq %dropend% >>new\1389.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1390.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1390.html ' ) do if %%i leq %dropend% >>new\1390.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1391.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1391.html ' ) do if %%i leq %dropend% >>new\1391.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1392.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1392.html ' ) do if %%i leq %dropend% >>new\1392.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1393.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1393.html ' ) do if %%i leq %dropend% >>new\1393.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1394.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1394.html ' ) do if %%i leq %dropend% >>new\1394.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1395.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1395.html ' ) do if %%i leq %dropend% >>new\1395.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1396.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1396.html ' ) do if %%i leq %dropend% >>new\1396.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1397.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1397.html ' ) do if %%i leq %dropend% >>new\1397.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1398.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1398.html ' ) do if %%i leq %dropend% >>new\1398.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1399.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1399.html ' ) do if %%i leq %dropend% >>new\1399.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1400.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1400.html ' ) do if %%i leq %dropend% >>new\1400.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1401.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1401.html ' ) do if %%i leq %dropend% >>new\1401.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1402.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1402.html ' ) do if %%i leq %dropend% >>new\1402.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1403.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1403.html ' ) do if %%i leq %dropend% >>new\1403.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1404.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1404.html ' ) do if %%i leq %dropend% >>new\1404.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1405.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1405.html ' ) do if %%i leq %dropend% >>new\1405.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1406.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1406.html ' ) do if %%i leq %dropend% >>new\1406.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1407.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1407.html ' ) do if %%i leq %dropend% >>new\1407.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1408.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1408.html ' ) do if %%i leq %dropend% >>new\1408.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1409.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1409.html ' ) do if %%i leq %dropend% >>new\1409.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1410.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1410.html ' ) do if %%i leq %dropend% >>new\1410.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1411.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1411.html ' ) do if %%i leq %dropend% >>new\1411.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1412.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1412.html ' ) do if %%i leq %dropend% >>new\1412.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1413.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1413.html ' ) do if %%i leq %dropend% >>new\1413.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1414.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1414.html ' ) do if %%i leq %dropend% >>new\1414.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1415.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1415.html ' ) do if %%i leq %dropend% >>new\1415.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1416.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1416.html ' ) do if %%i leq %dropend% >>new\1416.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1417.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1417.html ' ) do if %%i leq %dropend% >>new\1417.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1418.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1418.html ' ) do if %%i leq %dropend% >>new\1418.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1419.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1419.html ' ) do if %%i leq %dropend% >>new\1419.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1420.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1420.html ' ) do if %%i leq %dropend% >>new\1420.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1421.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1421.html ' ) do if %%i leq %dropend% >>new\1421.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1422.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1422.html ' ) do if %%i leq %dropend% >>new\1422.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1423.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1423.html ' ) do if %%i leq %dropend% >>new\1423.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1424.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1424.html ' ) do if %%i leq %dropend% >>new\1424.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1425.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1425.html ' ) do if %%i leq %dropend% >>new\1425.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1426.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1426.html ' ) do if %%i leq %dropend% >>new\1426.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1427.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1427.html ' ) do if %%i leq %dropend% >>new\1427.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1428.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1428.html ' ) do if %%i leq %dropend% >>new\1428.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1429.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1429.html ' ) do if %%i leq %dropend% >>new\1429.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1430.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1430.html ' ) do if %%i leq %dropend% >>new\1430.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1431.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1431.html ' ) do if %%i leq %dropend% >>new\1431.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1432.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1432.html ' ) do if %%i leq %dropend% >>new\1432.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1433.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1433.html ' ) do if %%i leq %dropend% >>new\1433.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1434.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1434.html ' ) do if %%i leq %dropend% >>new\1434.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1435.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1435.html ' ) do if %%i leq %dropend% >>new\1435.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1436.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1436.html ' ) do if %%i leq %dropend% >>new\1436.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1437.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1437.html ' ) do if %%i leq %dropend% >>new\1437.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1438.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1438.html ' ) do if %%i leq %dropend% >>new\1438.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1439.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1439.html ' ) do if %%i leq %dropend% >>new\1439.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1440.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1440.html ' ) do if %%i leq %dropend% >>new\1440.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1441.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1441.html ' ) do if %%i leq %dropend% >>new\1441.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1442.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1442.html ' ) do if %%i leq %dropend% >>new\1442.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1443.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1443.html ' ) do if %%i leq %dropend% >>new\1443.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1444.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1444.html ' ) do if %%i leq %dropend% >>new\1444.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1445.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1445.html ' ) do if %%i leq %dropend% >>new\1445.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1446.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1446.html ' ) do if %%i leq %dropend% >>new\1446.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1447.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1447.html ' ) do if %%i leq %dropend% >>new\1447.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1448.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1448.html ' ) do if %%i leq %dropend% >>new\1448.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1449.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1449.html ' ) do if %%i leq %dropend% >>new\1449.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1450.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1450.html ' ) do if %%i leq %dropend% >>new\1450.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1451.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1451.html ' ) do if %%i leq %dropend% >>new\1451.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1452.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1452.html ' ) do if %%i leq %dropend% >>new\1452.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1453.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1453.html ' ) do if %%i leq %dropend% >>new\1453.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1454.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1454.html ' ) do if %%i leq %dropend% >>new\1454.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1455.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1455.html ' ) do if %%i leq %dropend% >>new\1455.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1456.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1456.html ' ) do if %%i leq %dropend% >>new\1456.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1457.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1457.html ' ) do if %%i leq %dropend% >>new\1457.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1458.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1458.html ' ) do if %%i leq %dropend% >>new\1458.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1459.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1459.html ' ) do if %%i leq %dropend% >>new\1459.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1460.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1460.html ' ) do if %%i leq %dropend% >>new\1460.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1461.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1461.html ' ) do if %%i leq %dropend% >>new\1461.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1462.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1462.html ' ) do if %%i leq %dropend% >>new\1462.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1463.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1463.html ' ) do if %%i leq %dropend% >>new\1463.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1464.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1464.html ' ) do if %%i leq %dropend% >>new\1464.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1465.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1465.html ' ) do if %%i leq %dropend% >>new\1465.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1466.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1466.html ' ) do if %%i leq %dropend% >>new\1466.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1467.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1467.html ' ) do if %%i leq %dropend% >>new\1467.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1468.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1468.html ' ) do if %%i leq %dropend% >>new\1468.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1469.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1469.html ' ) do if %%i leq %dropend% >>new\1469.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1470.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1470.html ' ) do if %%i leq %dropend% >>new\1470.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1471.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1471.html ' ) do if %%i leq %dropend% >>new\1471.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1472.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1472.html ' ) do if %%i leq %dropend% >>new\1472.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1473.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1473.html ' ) do if %%i leq %dropend% >>new\1473.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1474.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1474.html ' ) do if %%i leq %dropend% >>new\1474.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1475.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1475.html ' ) do if %%i leq %dropend% >>new\1475.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1476.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1476.html ' ) do if %%i leq %dropend% >>new\1476.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1477.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1477.html ' ) do if %%i leq %dropend% >>new\1477.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1478.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1478.html ' ) do if %%i leq %dropend% >>new\1478.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1479.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1479.html ' ) do if %%i leq %dropend% >>new\1479.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1480.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1480.html ' ) do if %%i leq %dropend% >>new\1480.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1481.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1481.html ' ) do if %%i leq %dropend% >>new\1481.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1482.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1482.html ' ) do if %%i leq %dropend% >>new\1482.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1483.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1483.html ' ) do if %%i leq %dropend% >>new\1483.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1484.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1484.html ' ) do if %%i leq %dropend% >>new\1484.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1485.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1485.html ' ) do if %%i leq %dropend% >>new\1485.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1486.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1486.html ' ) do if %%i leq %dropend% >>new\1486.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1487.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1487.html ' ) do if %%i leq %dropend% >>new\1487.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1488.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1488.html ' ) do if %%i leq %dropend% >>new\1488.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1489.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1489.html ' ) do if %%i leq %dropend% >>new\1489.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1490.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1490.html ' ) do if %%i leq %dropend% >>new\1490.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1491.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1491.html ' ) do if %%i leq %dropend% >>new\1491.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1492.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1492.html ' ) do if %%i leq %dropend% >>new\1492.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1493.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1493.html ' ) do if %%i leq %dropend% >>new\1493.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1494.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1494.html ' ) do if %%i leq %dropend% >>new\1494.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1495.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1495.html ' ) do if %%i leq %dropend% >>new\1495.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1496.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1496.html ' ) do if %%i leq %dropend% >>new\1496.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1497.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1497.html ' ) do if %%i leq %dropend% >>new\1497.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1498.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1498.html ' ) do if %%i leq %dropend% >>new\1498.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1499.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1499.html ' ) do if %%i leq %dropend% >>new\1499.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
set droptop=37
for /f %%i in ( ' find /c /v "" ^<1500.html ' ) do set /a dropend=%%i-20
for /f "skip=%droptop%tokens=1*delims=][" %%i in ( ' find /n /v ""
^<1500.html ' ) do if %%i leq %dropend% >>new\1500.html echo\%%j
for %%i in (droptop dropend) do (set %%i=)
