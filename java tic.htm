const board = document.getElementById('board');
const statusElement = document.getElementById('status');
let currentPlayer = 'X';
let boardState = ['', '', '', '', '', '', '', '', '']; // Empty board

const winningCombinations = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  [0, 4, 8],
  [2, 4, 6]
];

// Create the Tic-Tac-Toe board
board.addEventListener('click', handleCellClick);

function handleCellClick(event) {
  const index = event.target.dataset.index;
  
  // Ignore if cell is already taken or if the game is over
  if (boardState[index] !== '' || statusElement.textContent !== '') return;

  // Mark the cell with current player's symbol
  boardState[index] = currentPlayer;
  event.target.textContent = currentPlayer;
  event.target.classList.add('taken');
  
  // Check for a winner
  if (checkWinner()) {
    statusElement.textContent = `${currentPlayer} Wins! Redirecting...`;
    setTimeout(() => redirectToNewPage(), 2000);
    return;
  }

  // Check for a draw
  if (boardState.every(cell => cell !== '')) {
    statusElement.textContent = 'It\'s a Draw! Redirecting...';
    setTimeout(() => redirectToNewPage(), 2000);
    return;
  }

  // Switch player
  currentPlayer = currentPlayer === 'X' ? 'O' : 'X';
  statusElement.textContent = `${currentPlayer}'s turn`;
}

function checkWinner() {
  return winningCombinations.some(combination => {
    const [a, b, c] = combination;
    return boardState[a] === currentPlayer && boardState[b] === currentPlayer && boardState[c] === currentPlayer;
  });
}

function redirectToNewPage() {
  window.location.href = "newpage.html"; // Change this to your desired URL
}
