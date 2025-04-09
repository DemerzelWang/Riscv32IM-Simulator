## Project Structure

- `src`: Source code
- `include`: ELFIO headers
- `test-*`: Test case folders

## Useful Scripts

- `build-test.sh`: Builds ELF files for the following test cases. You can find the ELF files and objdumped files under `/riscv-elf`:
  - `build-test-basic.sh`
  - `build-test-inclass.sh`
  - `build-test-fused.sh`
- `run-simulator`: Runs all ELF files under `/riscv-elf` and outputs results to `/results`.
