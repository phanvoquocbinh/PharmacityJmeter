cat > README.md << 'EOF'
# JMeter CI Demo

Run JMeter test plan in CI with GitHub Actions.
- Test plan: `tests/Pharmacy_Performance.jmx`

## Run locally (CLI)
jmeter -n -t tests/Pharmacy_Performance.jmx -l results/results.jtl -e -o results/report
EOF
