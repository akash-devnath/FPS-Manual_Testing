# Player System – Test Documentation

## 1. Test Information

| Field | Details |
|---|---|
| Game | FPS Shooter |
| Engine | Unity 6 |
| Platform | Windows PC |
| Testing Type | Manual Functional Testing |
| Test Management | Jira |

## 2. Player System Testing

**Jira Story:** FGT-2

**Objective:** Verify the functionality of the player system, including movement, jumping, camera controls, health, and collision behaviour.

### Testing Scope
- Player Movement
- Player Jump
- Camera Controls
- Player Health and Death
- Player Collision and Physics

## 3. Player Movement Testing

**Jira Subtask:** FGT-3

**Objective:** Verify that player movement functions correctly and consistently during gameplay.

| Test ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| PM-01 | Forward movement (W) | Player moves forward | PASS |
| PM-02 | Backward movement (S) | Player moves backward | PASS |
| PM-03 | Left movement (A) | Player moves left | PASS |
| PM-04 | Right movement (D) | Player moves right | PASS |
| PM-05 | Diagonal movement | Player moves diagonally as expected | PASS |
| PM-06 | Sprint functionality | Player moves faster while sprinting | PASS |
| PM-07 | Movement responsiveness | Player responds correctly to keyboard inputs | PASS |
| PM-08 | Movement speed consistency | Movement speed remains consistent | PASS |
| PM-09 | Collision with walls and obstacles | Player does not pass through solid obstacles | PASS |

**Execution Result:** Tested player movement using keyboard inputs. The tested movement scenarios behaved as expected.

**Evidence:** Gameplay recording and Jira execution result.

## 4. Player Jump Testing

**Jira Subtask:** FGT-4

**Objective:** Verify single-jump functionality and landing behaviour.

| Test ID | Test Scenario | Expected Result | Status |
|---|---|---|---|
| PJ-01 | Press jump while grounded | Player performs a single jump | Update |
| PJ-02 | Attempt another jump while airborne | Player cannot perform a second jump | Update |
| PJ-03 | Land after jumping | Player returns to grounded state | Update |
| PJ-04 | Jump repeatedly after landing | Player can jump again after landing | Update |

**Execution Result:** Record the actual result after verifying each scenario.

**Evidence:** Add gameplay screenshots or recording.

## 5. Test Execution Summary

| Testing Area | Status |
|---|---|
| Player Movement | Passed |
| Player Jump | Update with verified results |
