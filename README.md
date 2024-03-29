# File Structure



- `rolebench-eng/instruction-generalization`, `rolebench-eng/role-generalization`, and `rolebench-zh`: All contain two subfolders: `general` and `role_specific`. Each subfolder has training data, testing data, and the RoleGPT baseline results for comparison.
- `rolegpt baseline`:  A strong baseline for performance comparison. RoleGPT is Role Prompting using GPT for speaking style imitation. In the case of general instructions, we generate 6 responses using RoleGPT for each role-instruction pair; 5 of these serve as ground truth candidates, while the remaining one functions as a RoleGPT strong baseline.
