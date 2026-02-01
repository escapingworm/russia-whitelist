# Russia whitelist
List of IP ranges was manually checked on MTS while the whitelists were active.

Actual link to the IP ranges:
```
https://raw.githubusercontent.com/escapingworm/russia-whitelist/refs/heads/main/ru-whitelist-cidr.txt
```

## Data Format

Each file contains a list of subnets in CIDR format, one entry per line.

Example:
```text
10.0.0.0/8
192.168.0.0/16
91.206.132.0/22
```

## Sources and Accuracy

Data is aggregated from open sources and scanning results. Updates occur as changes are detected. Whitelists may be changed by operators without notice. Use at your own risk.
## Contributing

If you have new data or corrections:
1.  Fork the repository.
2.  Make your changes.
3.  Submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

*Disclaimer: This data is for educational and research purposes only. The maintainers are not responsible for any network disruptions or legal issues arising from the use of this information.*
