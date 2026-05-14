# Decision Mining Results

Following the methodology of de Leoni & van der Aalst (2013).

## Gateway: `p_4`
- **CV-Accuracy:** 0.939
- **Observations:** 608
- **Klassen:** W_Handle leads, τ(skip_2)

**→ `τ(skip_2)`**
```
(current_resource ≤ 0.50 ∧ time_since_start_h ≤ 0.02 ∧ case:RequestedAmount ≤ 10250.00 ∧ case:RequestedAmount ≤ 9500.00) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h ≤ 0.02 ∧ case:RequestedAmount ≤ 10250.00 ∧ case:RequestedAmount > 9500.00 ∧ time_since_start_h ≤ 0.01) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h ≤ 0.02 ∧ case:RequestedAmount ≤ 10250.00 ∧ case:RequestedAmount > 9500.00 ∧ time_since_start_h > 0.01) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h ≤ 0.02 ∧ case:RequestedAmount > 10250.00 ∧ case:LoanGoal ≤ 1.50) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h ≤ 0.02 ∧ case:RequestedAmount > 10250.00 ∧ case:LoanGoal > 1.50) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h > 0.02 ∧ time_since_start_h ≤ 0.02 ∧ time_since_start_h ≤ 0.02) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h > 0.02 ∧ time_since_start_h > 0.02 ∧ time_since_start_h ≤ 0.03) ∨ (current_resource ≤ 0.50 ∧ time_since_start_h > 0.02 ∧ time_since_start_h > 0.02 ∧ time_since_start_h > 0.03)
```

**→ `W_Handle leads`**
```
(current_resource ≤ 0.50 ∧ time_since_start_h > 0.02 ∧ time_since_start_h ≤ 0.02 ∧ time_since_start_h > 0.02) ∨ (current_resource > 0.50 ∧ time_since_start_h ≤ 0.99) ∨ (current_resource > 0.50 ∧ time_since_start_h > 0.99)
```

## Gateway: `p_37`
- **CV-Accuracy:** 0.574
- **Observations:** 765
- **Klassen:** O_Accepted, τ(skip_25)

**→ `O_Accepted`**
```
(current_resource ≤ 3.50) ∨ (current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource ≤ 28.50 ∧ current_resource ≤ 20.50 ∧ current_resource > 18.50) ∨ (current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource > 28.50 ∧ time_since_start_h ≤ 302.30) ∨ (current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource > 28.50 ∧ time_since_start_h > 302.30) ∨ (current_resource > 3.50 ∧ time_since_start_h > 484.84 ∧ current_resource ≤ 36.50 ∧ current_resource ≤ 22.50 ∧ current_resource ≤ 17.50) ∨ (current_resource > 3.50 ∧ time_since_start_h > 484.84 ∧ current_resource ≤ 36.50 ∧ current_resource ≤ 22.50 ∧ current_resource > 17.50) ∨ (current_resource > 3.50 ∧ time_since_start_h > 484.84 ∧ current_resource > 36.50)
```

**→ `τ(skip_25)`**
```
(current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource ≤ 28.50 ∧ current_resource ≤ 20.50 ∧ current_resource ≤ 18.50) ∨ (current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource ≤ 28.50 ∧ current_resource > 20.50 ∧ case:LoanGoal ≤ 2.50) ∨ (current_resource > 3.50 ∧ time_since_start_h ≤ 484.84 ∧ current_resource ≤ 28.50 ∧ current_resource > 20.50 ∧ case:LoanGoal > 2.50) ∨ (current_resource > 3.50 ∧ time_since_start_h > 484.84 ∧ current_resource ≤ 36.50 ∧ current_resource > 22.50)
```
