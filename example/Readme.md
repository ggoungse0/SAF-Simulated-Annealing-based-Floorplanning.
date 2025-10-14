## [hp] initial condition(made by partial SA) + 1st SA(iter1000) + 2nd SA(iter3000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### hp(DeadSpace ratio = 4.07%)
#### initial condition(made by partial SA)
![Figure_2](https://github.com/user-attachments/assets/8a9cef7e-60f3-4e9d-a274-5205ca6eb9e1)
=== 부분 SA 후 Chip 상태 ===

경계 상자: W=6538.00, H=1554.00, 면적=10160052.00

HPWL (절대값)             = 0.00

정규화된 면적             = 575.276

정규화된 HPWL             = 0.000

정규화된 페널티          = 38.811

정규화된 DeadSpace       = 13.085

부분 SA 후 비용 (페널티만 사용) = 0.418

![Figure_4](https://github.com/user-attachments/assets/5d5a5fdf-5684-4d77-ade6-cc463059686b)
![Figure_5](https://github.com/user-attachments/assets/a8f1a4f1-07c4-4a16-8a25-eb80fe9eed3b)


=== 1단계 SA + Compaction 후 상태 (참고용 Dead Space 포함 비용) ===

경계 상자: W=6160.00, H=1596.00, 면적=9831360.00

HPWL (절대값) = 0.00, 정규화된 HPWL = 0.000

정규화된 면적 = 556.665, 정규화된 페널티 = 31.151

정규화된 DeadSpace = 10.179, 실제 DeadSpace = 1000776.00 (10.18%)

비용 (모든 항 포함) = 1.213

![Figure_7](https://github.com/user-attachments/assets/c10255e7-41c4-4506-a6f9-ade40ef9b202)
![Figure_8](https://github.com/user-attachments/assets/53db3fa0-d02f-48a7-aef0-57a99284f68f)

=== 최종 Compaction 후 (2단계 SA 결과 기반) ===

최종 Compaction 후 경계 상자: W=3304.00, H=2786.00, 면적=9204944.00

최종 Compaction 후 HPWL (절대값)         = 0.00

최종 Compaction 후 정규화된 면적         = 521.197

최종 Compaction 후 정규화된 HPWL         = 0.000

최종 Compaction 후 정규화된 페널티      = 0.178

최종 Compaction 후 정규화된 DeadSpace  = 4.067

최종 Compaction 후 실제 DeadSpace 면적 = 374360.00 (4.07%)

최종 Compaction 후 비용 (w_area=0.66, r_penalty=1.00, r_ds=80.00) = 0.670

## [apte] initial condition(made by partial SA) + 1st SA(iter2000) + 2nd SA(iter40000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### apte(DeadSpace ratio = 3.25%)
#### initial condition(made by partial SA)
![image](https://github.com/user-attachments/assets/cffbdbf2-d78a-4c45-af46-421de55cbe16)


=== 부분 SA 후 Chip 상태 ===

경계 상자: W=9438.00, H=5490.00, 면적=51814620.00

HPWL (절대값)             = 0.00

정규화된 면적             = 556.409

정규화된 HPWL             = 0.000

정규화된 페널티          = 2.929

정규화된 DeadSpace       = 10.138

부분 SA 후 비용 (페널티만 사용) = 0.370

![image](https://github.com/user-attachments/assets/1765ba27-d9f0-46b6-adcf-01bb9c3bced9)
![image](https://github.com/user-attachments/assets/0d382a31-500d-449c-86a7-940ae5d76c66)

=== 1단계 SA + Compaction 후 상태 (참고용 Dead Space 포함 비용) ===

경계 상자: W=9438.00, H=5490.00, 면적=51814620.00

HPWL (절대값) = 0.00, 정규화된 HPWL = 0.000

정규화된 면적 = 556.409, 정규화된 페널티 = 2.929

정규화된 DeadSpace = 10.138, 실제 DeadSpace = 5252992.00 (10.14%)

비용 (모든 항 포함) = 1.181

![image](https://github.com/user-attachments/assets/576757b7-a043-4677-8b57-78dc11a35e2d)
![image](https://github.com/user-attachments/assets/2a28c3f2-72ae-4c8d-9769-597f3f4a87de)

=== 최종 Compaction 후 (2단계 SA 결과 기반) ===

최종 Compaction 후 경계 상자: W=6578.00, H=7316.00, 면적=48124648.00

최종 Compaction 후 HPWL (절대값)         = 0.00

최종 Compaction 후 정규화된 면적         = 516.784

최종 Compaction 후 정규화된 HPWL         = 0.000

최종 Compaction 후 정규화된 페널티      = 0.000

최종 Compaction 후 정규화된 DeadSpace  = 3.248

최종 Compaction 후 실제 DeadSpace 면적 = 1563020.00 (3.25%)

최종 Compaction 후 비용 (w_area=0.66, r_penalty=1.00, r_ds=80.00) = 0.601

## [ami33] initial condition(made by partial SA) + 1st SA(iter5000) + 2nd SA(iter45000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### ami33(DeadSpace ratio = 2.17%)
#### Final compaction
<img width="2984" height="1486" alt="floorplan_Final_Compacted_Layout" src="https://github.com/user-attachments/assets/165f74ca-2fbf-429d-bd79-ebde4ff5ece1" />

[Info] 플롯이 floorplan_3rd_SA_Result.png으로 저장되었습니다.

[Info] 최종 결과에 Compaction 수행 중...

[Info] --- 최종 Greedy Compaction 수행 (왼쪽 -> 아래쪽) ---
[Info] --- 최종 Greedy Compaction 완료 ---

=== 최종 Compaction 후 결과 ===
최종 Compaction 후 경계 상자: W=1141.00, H=1036.00, 면적=1182076.00
최종 Compaction 후 HPWL (절대값)         = 0.00
최종 Compaction 후 실제 DeadSpace 면적 = 25627.00 (2.17%)
최종 Compaction 후 비용 (모든 항 포함)  = 2.554
최종 Compaction 후 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_Final_Compacted_Layout.png으로 저장되었습니다.

플로어플래닝 프로세스 완료.
최종 결과 요약:
  - 최종 칩 면적: 1182076.00
  - 최종 HPWL: 0.00
  - 최종 DeadSpace: 2.17%
  - 최종 비용: 2.554
모든 플롯이 PNG 파일로 저장되었습니다.




## [ami49] initial condition(made by partial SA) + 1st SA(iter2000) + 2nd SA(iter35000) 
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### ami49(DeadSpace ratio = 2.22%)
#### Final compaction

<img width="2961" height="1526" alt="floorplan_Final_Compacted_Layout" src="https://github.com/user-attachments/assets/4e73de3f-9c21-4795-b722-d17f68ccb65d" />

[Info] 플롯이 floorplan_3rd_SA_Result.png으로 저장되었습니다.

[Info] 최종 결과에 Compaction 수행 중...

[Info] --- 최종 Greedy Compaction 수행 (왼쪽 -> 아래쪽) ---
[Info] --- 최종 Greedy Compaction 완료 ---

=== 최종 Compaction 후 결과 ===
최종 Compaction 후 경계 상자: W=6300.00, H=5754.00, 면적=36250200.00
최종 Compaction 후 HPWL (절대값)         = 0.00
최종 Compaction 후 실제 DeadSpace 면적 = 804776.00 (2.22%)
최종 Compaction 후 비용 (모든 항 포함)  = 3.017
최종 Compaction 후 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_Final_Compacted_Layout.png으로 저장되었습니다.

플로어플래닝 프로세스 완료.
최종 결과 요약:
  - 최종 칩 면적: 36250200.00
  - 최종 HPWL: 0.00
  - 최종 DeadSpace: 2.22%
  - 최종 비용: 3.017
모든 플롯이 PNG 파일로 저장되었습니다.




## [n100] initial condition(made by partial SA) + 1st SA(iter3000) + 2nd SA(iter5000) + 3rd SA(40000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### n100(DeadSpace ratio = 3.14%)
#### Final compaction

<img width="2979" height="1537" alt="floorplan_Final_Compacted_Layout" src="https://github.com/user-attachments/assets/290eb37b-12d1-4aaa-83bd-1503d29e2193" />

[Info] 플롯이 floorplan_3rd_SA_Result.png으로 저장되었습니다.

[Info] 최종 결과에 Compaction 수행 중...

[Info] --- 최종 Greedy Compaction 수행 (왼쪽 -> 아래쪽) ---
[Info] --- 최종 Greedy Compaction 완료 ---

=== 최종 Compaction 후 결과 ===
최종 Compaction 후 경계 상자: W=432.00, H=429.00, 면적=185328.00
최종 Compaction 후 HPWL (절대값)         = 234545.00
최종 Compaction 후 실제 DeadSpace 면적 = 5827.00 (3.14%)
최종 Compaction 후 비용 (모든 항 포함)  = 4.006
최종 Compaction 후 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_Final_Compacted_Layout.png으로 저장되었습니다.

플로어플래닝 프로세스 완료.
최종 결과 요약:
  - 최종 칩 면적: 185328.00
  - 최종 HPWL: 234545.00
  - 최종 DeadSpace: 3.14%
  - 최종 비용: 4.006
모든 플롯이 PNG 파일로 저장되었습니다.







## [n200] initial condition(made by partial SA) + 1st SA(iter3000) + 2nd SA(iter3000) + 3rd SA(iter 40000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### n200(DeadSpace ratio = 4.31%)
#### Final compaction

<img width="2984" height="1536" alt="floorplan_Final_Compacted_Layout" src="https://github.com/user-attachments/assets/fb3457f9-73c4-41cd-a606-e188bca2e792" />

[Info] 플롯이 floorplan_3rd_SA_Result.png으로 저장되었습니다.

[Info] 최종 결과에 Compaction 수행 중...

[Info] --- 최종 Greedy Compaction 수행 (왼쪽 -> 아래쪽) ---
[Info] --- 최종 Greedy Compaction 완료 ---

=== 최종 Compaction 후 결과 ===
최종 Compaction 후 경계 상자: W=466.00, H=394.00, 면적=183604.00
최종 Compaction 후 HPWL (절대값)         = 398427.00
최종 Compaction 후 실제 DeadSpace 면적 = 7908.00 (4.31%)
최종 Compaction 후 비용 (모든 항 포함)  = 4.868
최종 Compaction 후 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_Final_Compacted_Layout.png으로 저장되었습니다.

플로어플래닝 프로세스 완료.
최종 결과 요약:
  - 최종 칩 면적: 183604.00
  - 최종 HPWL: 398427.00
  - 최종 DeadSpace: 4.31%
  - 최종 비용: 4.868
모든 플롯이 PNG 파일로 저장되었습니다.



## [n300] initial condition(made by partial SA) + 1st SA(iter5000) + 2nd SA(iter45000)
### partial SA and 1st SA's cost function use AREA, HPWL, penalty(exceed the standard chip penalty)

(where standard chip is square which has width, height = sqrt(all modules area sum*1.2) )

### n300(DeadSpace ratio = 4.93%)
#### Final compaction

<img width="2983" height="1540" alt="floorplan_Final_Compacted_Layout" src="https://github.com/user-attachments/assets/0ced1d97-ca21-4a17-b33e-cb2a827d953f" />

3단계 SA 최적화 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_3rd_SA_Result.png으로 저장되었습니다.

[Info] 최종 결과에 Compaction 수행 중...

[Info] --- 최종 Greedy Compaction 수행 (왼쪽 -> 아래쪽) ---
[Info] --- 최종 Greedy Compaction 완료 ---

=== 최종 Compaction 후 결과 ===
최종 Compaction 후 경계 상자: W=577.00, H=498.00, 면적=287346.00
최종 Compaction 후 HPWL (절대값)         = 574728.00
최종 Compaction 후 실제 DeadSpace 면적 = 14176.00 (4.93%)
최종 Compaction 후 비용 (모든 항 포함)  = 5.884
최종 Compaction 후 레이아웃 플로팅 중...
[Info] 플롯이 floorplan_Final_Compacted_Layout.png으로 저장되었습니다.

플로어플래닝 프로세스 완료.
최종 결과 요약:
  - 최종 칩 면적: 287346.00
  - 최종 HPWL: 574728.00
  - 최종 DeadSpace: 4.93%
  - 최종 비용: 5.884
모든 플롯이 PNG 파일로 저장되었습니다.
