# Modal-Master
 <h1>Modal Master</h1>

  <p><strong>Modal Master</strong> is a simple, elegant JavaScript component for creating and managing modal windows. This project showcases the use of basic JavaScript to handle UI elements, providing functionality for opening and closing modal windows using buttons, overlay clicks, and keyboard events.</p>

  <h2>Features</h2>
  <ul>
    <li><strong>Open Modal:</strong> Click on any of the designated buttons to open the modal window.</li>
    <li><strong>Close Modal:</strong> Close the modal window by clicking the close button, clicking outside the modal (on the overlay), or pressing the "Escape" key.</li>
    <li><strong>Overlay Support:</strong> An overlay is displayed behind the modal to focus user attention.</li>
  </ul>
    <h2>Explanation</h2>
  <ul>
    <li><strong>openModal Function:</strong> This function removes the <code>hidden</code> class from the modal and overlay, making them visible.</li>
    <li><strong>closeModal Function:</strong> This function adds the <code>hidden</code> class to the modal and overlay, hiding them.</li>
    <li><strong>Event Listeners:</strong></li>
    <ul>
      <li>Click event listeners on buttons with the <code>show-modal</code> class to open the modal.</li>
      <li>A click event listener on the close button to close the modal.</li>
      <li>A click event listener on the overlay to close the modal.</li>
      <li>A keydown event listener on the document to close the modal when the "Escape" key is pressed.</li>
    </ul>
  </ul>
