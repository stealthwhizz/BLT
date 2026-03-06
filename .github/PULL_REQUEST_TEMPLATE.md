## Description
<!-- Provide a clear and concise description of what this PR does -->


## Related Issue
<!-- Link to the issue this PR addresses -->
Fixes #<!-- issue number -->

## Type of Change
<!-- Mark the relevant option with an 'x' -->
- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature (non-breaking change that adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update
- [ ] Style/UI update (no functional changes)
- [ ] Refactoring (no functional changes)
- [ ] Performance improvement
- [ ] Test update
- [ ] Configuration change

## Changes Made
<!-- Provide a detailed list of changes -->

### Modified Components
- **File/Component:** `path/to/file.py`
  - **Change:** <!-- Describe what changed and why -->
  
### Added Components
- **File/Component:** `path/to/new_file.py`
  - **Purpose:** <!-- Describe what this adds -->

### Deleted Components
- **File/Component:** `path/to/removed_file.py`
  - **Reason:** <!-- Explain why this was removed -->

## Root Cause (for bug fixes)
<!-- If fixing a bug, explain what caused it -->

**Before (problematic code):**
```python
# Original code causing the issue
```

**After (fixed code):**
```python
# New code that resolves the issue
```

## Testing
<!-- Describe the tests you've added or run -->

### Test Cases Added/Modified
- [ ] `tests/path/to/test_file.py::test_name`
- [ ] <!-- Add more test cases -->

### How to Test
```bash
# Commands to run tests
pytest tests/path/to/test_file.py -v
```

### Manual Testing Steps
1. 
2. 
3. 

### Test Results
<!-- Paste test output or screenshots showing tests pass -->
```
# Test output
```

## Screenshots (if applicable)
<!-- Add screenshots showing before/after for UI changes -->

**Before:**
<!-- Screenshot or description of old behavior -->

**After:**
<!-- Screenshot or description of new behavior -->

## Checklist
<!-- Mark completed items with an 'x' -->
- [ ] My code follows the project's style guidelines
- [ ] I have performed a self-review of my code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings or errors
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published
- [ ] I have checked my code and corrected any misspellings
- [ ] I have updated the CHANGELOG (if applicable)

## Breaking Changes
<!-- If this introduces breaking changes, list them here -->
- [ ] This PR introduces breaking changes

**Details:**
<!-- Describe what breaks and how users should migrate -->


## Performance Impact
<!-- Describe any performance implications -->
- [ ] No performance impact
- [ ] Performance improved
- [ ] Performance degraded (explain why this is acceptable)

**Details:**
<!-- Add benchmarks or profiling results if relevant -->


## Security Considerations
<!-- Describe any security implications -->
- [ ] No security impact
- [ ] Security improved
- [ ] Requires security review

**Details:**


## Deployment Notes
<!-- Any special deployment considerations? -->
- [ ] Requires database migrations
- [ ] Requires environment variable changes
- [ ] Requires dependency updates
- [ ] Requires configuration changes

**Details:**
```bash
# Commands or steps needed for deployment
```

## Rollback Plan
<!-- How can this change be rolled back if needed? -->


## Additional Context
<!-- Any other context, dependencies, or information reviewers should know -->


## Reviewer Notes
<!-- Specific areas where you want reviewer feedback -->
- [ ] <!-- e.g., Please review the error handling logic -->
- [ ] <!-- e.g., Focus on the authentication changes -->

---

<!-- 
For Reviewers:
- Verify all checklist items are completed
- Test the changes locally if possible
- Check for potential edge cases
- Ensure code quality and maintainability
-->
