# Day 10 Reliability Final Report

## Metrics Summary

| Metric | Value |
|---|---:|
| total_requests | 300 |
| availability | 0.9867 |
| error_rate | 0.0133 |
| latency_p50_ms | 280.52 |
| latency_p95_ms | 321.03 |
| latency_p99_ms | 323.15 |
| fallback_success_rate | 0.9545 |
| cache_hit_rate | 0.63 |
| circuit_open_count | 10 |
| recovery_time_ms | 2387.838125228882 |
| estimated_cost | 0.04259 |
| estimated_cost_saved | 0.189 |

## Chaos Scenarios

| Scenario | Status |
|---|---|
| primary_timeout_100 | pass |
| primary_flaky_50 | pass |
| all_healthy | pass |

## Analysis TODO(student)

Explain what failed, why the fallback path worked or did not work, and what you would change before production.