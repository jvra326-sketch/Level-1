# 1. Create and write your Phase 3 notes
echo "# Phase 3: Infrastructure Traffic Analysis" > phase3-traffic.md
echo "- **Established Connections**: Inspected active socket traffic via netstat, verifying outbound TLS sessions on port 443." >> phase3-traffic.md

# 2. Stage the new file so git tracks it
git add phase3-traffic.md

# 3. Run your auto-sync script to push it to GitHub
/Users/jveeru326/git-practice/autosync.sh
